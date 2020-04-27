# CNT_TFT_PDK

Motivation:
Carbon nanotube (CNT) thin-film transistor (TFT) technology is an organic transistor technology with a typical supply voltage of 3V. The detailed information about the 
technology is given in R2. We developed the standard cell libraries for the CNT-TFT technology
by characterizing the combinational and sequential logic gates. The characteristics of the libraries are reported in our paper Printed Microprocessors, published in ISCA 2020. 


Library Details:
The CNT-TFT standard libraries are developed using the compact model available at [R3]. 
Only p-type transistor is available in CNT-TFT technology and all logic gates are realized through psuedo CMOS logic [R2]. 
The ./lib folder contains the standard libraries for the supply voltage ranging from 2.6V to 3.6V.

[R2] Ting Lei, Lei-Lai Shao, Yu-Qing Zheng, Gregory Pitner, GuanhuaFang, Chenxin Zhu, Sicheng Li, Ray Beausoleil, H-S Philip Wong,Tsung-Ching Huang, et al. Low-voltage high-performance flexibledigital and analog circuits based on ultrahigh-purity semiconductingcarbon nanotubes.Nature communications, 10(1):2161, 2019
[R3] https://github.com/llshao/CNT-TFT-Verilog-A
