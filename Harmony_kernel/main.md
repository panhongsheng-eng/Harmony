<p align = "center">
 <img src = "https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=18D4F7&width=435&lines=Harmony+main%E5%87%BD%E6%95%B0%E5%88%86%E6%9E%90-Huawei%EF%BC%81">
  </p>
  
 <h2>1.源码</h2>
  <p align = "center">
 
 /*
 * Copyright (c) 2013-2019 Huawei Technologies Co., Ltd. All rights reserved.
 * Copyright (c) 2020-2021 Huawei Device Co., Ltd. All rights reserved.
 *
 * Redistribution and use in source and binary forms, with or without modification,
 * are permitted provided that the following conditions are met:
 *
 * 1. Redistributions of source code must retain the above copyright notice, this list of
 *    conditions and the following disclaimer.
 *
 * 2. Redistributions in binary form must reproduce the above copyright notice, this list
 *    of conditions and the following disclaimer in the documentation and/or other materials
 *    provided with the distribution.
 *
 * 3. Neither the name of the copyright holder nor the names of its contributors may be used
 *    to endorse or promote products derived from this software without specific prior written
 *    permission.
 *
 * THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
 * "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO,
 * THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR
 * PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR
 * CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL,
 * EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,
 * PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS;
 * OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY,
 * WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR
 * OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF
 * ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
 */
 
#include "los_config.h"
#include "los_sched_pri.h"
 
/**
 * @brief 
 * 内核入口函数,由汇编调用,见于reset_vector_up.S 和 reset_vector_mp.S 
 * up指单核CPU, mp指多核CPU bl        main
 * @return LITE_OS_SEC_TEXT_INIT 
 */
LITE_OS_SEC_TEXT_INIT INT32 main(VOID)//由主CPU执行,默认0号CPU 为主CPU 
{
    UINT32 ret = OsMain();
    if (ret != LOS_OK) {
        return (INT32)LOS_NOK;
    }
 
    CPU_MAP_SET(0, OsHwIDGet());//设置主CPU映射信息
 
    OsSchedStart();//调度开始
 
    while (1) {
        __asm volatile("wfi");//WFI: wait for Interrupt 等待中断，即下一次中断发生前都在此hold住不干活
    }
}
</p>
 <h2>2.函数</h2>
 <hr>
 <p>函数
LITE_OS_SEC_TEXT_INIT INT32 	main (VOID)
 	内核入口函数,由汇编调用,见于reset_vector_up.S 和 reset_vector_mp.S up指单核CPU, mp指多核CPU bl main
 </p>
 <h2>3.函数说明</h2>
 <p color = "red">
 ◆ main()
LITE_OS_SEC_TEXT_INIT INT32 main	(	VOID 		)	
内核入口函数,由汇编调用,见于reset_vector_up.S 和 reset_vector_mp.S up指单核CPU, mp指多核CPU bl main

返回
LITE_OS_SEC_TEXT_INIT
在文件 main.c 第 41 行定义.

{
    UINT32 ret = OsMain();
    if (ret != LOS_OK) {
        return (INT32)LOS_NOK;
    }
 
    CPU_MAP_SET(0, OsHwIDGet());//设置主CPU映射信息
 
    OsSchedStart();//调度开始
 
    while (1) {
        __asm volatile("wfi");//WFI: wait for Interrupt 等待中断，即下一次中断发生前都在此hold住不干活
    }
}
 </p>
  <h2>4.函数调用图</h2>
 <p align = "center">
 <img src = "https://user-images.githubusercontent.com/79436937/194769404-276e15d1-83fa-4eb9-b380-60684957756e.png">
 </p>
