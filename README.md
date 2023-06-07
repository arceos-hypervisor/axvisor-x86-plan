# 与Arceos结合的x86 Hypervisor - 项目计划

## 项目目标

基于之前同学的成果（未与ArceOS结合`x86`下的hypervisor，已与ArceOS结合的`RISC-V`下的hypervisor等），形成一个可以与arceos结合的`x86` hypervisor，通过feature机制进行各种特征的配置。

## 时间安排

> 以下为2023/06/07形成的第一步计划：

1. ***（06/13前）*** 通过现有的`RISC-V`下的模块化hypervisor和ArceOS现有的其他模块，了解ArceOS的模块机制及feature机制，并形成总结文档
2. ***（06/17前）*** 调研熟悉现有的`x86`下的hypervisor，进行详细对比，选择合适改造的hypervisor
3. ***（待前两步完成后细化，暂无具体时间）*** 详细阅读源码、改造hypervisor
