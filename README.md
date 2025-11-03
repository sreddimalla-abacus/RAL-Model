# RAL-Model
RAL MODEL EXAMPLE
This repository organizes the ChipVerify website code so that it is executable in a verification environment that uses the Register Abstraction Layer (RAL), as well as adding new features to the testbench.

UVM Register Model Example source code from ChipVerify

The above application refers to frontdoor access, as it performs writes and reads using the register model. However, there is also backdoor access, which in turn writes and reads directly to the DUT.

UVM Register Backdoor Access source code from ChipVerify

🔨 Project Features
Frontdoor Access
The model implemented for the abstraction layer of the registers is represented according to Figure 1, as well as its buses (CTL, STAT, TIMER_0 and TIMER_1) and respective fields.
