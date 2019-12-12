# CPU
- 暫存器(Register): 將要運算的資料，從記憶體抓出來後，會先把它暫存到 CPU 的一個空間
- 程式計數器: 是一個特殊的暫存器，專門用來存放下一個要被執行的指令
- 所在的記憶體位址。也可以叫它 Instruction Address Register 或 Instruction Counter。
依據不同架構的 CPU ，暫存器的數量會不同。像 ARM 和 MIPS 架構的處理器裡面便有 32 個暫存器。
- 寫入記憶體(memory write): 將運算完的結果送回記憶體>>>同時根據「程式計數器（Program Counter, PC）上記載的記憶體位址，取得下個指令
- 要設計 CPU 時，要制定的規格就是「指令集架構」（Instruction Set Architecture, ISA）。指令集架構包含了：
    - 指令集
    - 該指令集依附的機器結構敘述（Hardware Information）

![](/Pic/CPU2.jpg)

