An Ethernet based communication interface between two FPGAs through hardware description
on VHDL and Verilog. The UDP, IP, Ethernet, ARP and DHCP protocols are used for data flow and control over the
subnet.

Each folder has the top module till that folder and a testbench till that module (if exists).
System consists of complete : FPGA1, FPGA2, DHCP, Switch
The System module is in itself a testbench connecting all four entities.

**The FPGA1, FPGA2 and DHCP folders are complete in itself with appropriate testbenches with testing through file interface between each one of them among them.**

