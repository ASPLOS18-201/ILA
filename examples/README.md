## Examples for ILA.

[AES-RTL-C](https://github.com/ASPLOS18-201/ILA/tree/master/examples/AES-RTL-C) 
provides a tutorial on synthesizing ILAs for AES from RTL implementation and from C 
implementation.

[RBM](https://github.com/ASPLOS18-201/ILA/tree/master/examples/RBM) contains the case study where two ILAs of the Restricted Boltzmann machine accelerator are constructed and verified, w.r.t the SystemC and Verilog reference models, via ILA v.s. FSM equivalence checking.

[GB-Halide](https://github.com/ASPLOS18-201/ILA/tree/master/examples/GB-Halide) contains the case study where two ILAs of the Gaussian Blur accelerator, with different levels of abstraction, are constructed and verified. Both ILA v.s. ILA and ILA v.s. FSM equivalence checking are performed.

[RISC-V](https://github.com/ASPLOS18-201/ILA/tree/master/examples/RISC-V) constains the ILA of the RISC-V ISA and the verification framework that checks the equivalence between the ILA and the Rocket core RTL implementation.
