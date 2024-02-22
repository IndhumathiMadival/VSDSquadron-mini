## VSDSQUADRON-MINI
###  Install RISC-V GNU Toolchain first, then install Yosys, iverilog, gtkwave.

<b></p>1.install RISC-V GNU Toolchain :</p>

>- git clone https://github.com/riscv/riscv-gnu-toolchain</br>
  >- sudo apt-get install autoconf automake autotools-dev curl python3 python3-pip libmpc-dev libmpfr-dev libgmp-dev gawk build-essential bison flex texinfo gperf libtool
patchutils bc zlib1g-dev libexpat-dev ninja-build git cmake libglib2.0-dev</br>
>- ls
>- cd riscv-gnu-toolchain
  >- ./configure --prefix=/opt/riscv</br>
  >- make</br>
  
![Screenshot from 2024-02-21 15-42-04](https://github.com/HemaPriyaMudium/VSDSquadron-mini/assets/160724714/7b481b5b-dacf-4a36-aa50-de68c174d440)


<b></p>2.install Yosys:</p> 

>- git clone https://github.com/YosysHQ/yosys.git</br>
>- cd yosys</br>
>- sudo apt install make </br>
>- sudo apt-get install build-essential clang bison flex \libreadline-dev gawk tcl-dev libffi-dev git \graphviz xdot pkg-config python3 libboost-system-dev \libboost-python-dev libboost-filesystem-dev zlib1g-dev</br>
>- make config-gcc</br>
>- make</br>
>- sudo make install</br>


![Screenshot from 2024-02-21 22-55-21](https://github.com/HemaPriyaMudium/VSDSquadron-mini/assets/160724714/1188e7bd-f55e-42c9-bb4a-0a6c4e489848)


<b></p>3.install iverilog: </p>
>sudo apt-get install iverilog</br>

![Screenshot from 2024-02-21 22-34-24](https://github.com/HemaPriyaMudium/VSDSquadron-mini/assets/160724714/b53f70ff-227a-4002-92b1-9339148e2626)


<b></p>4.install gtkwave: </p>
>sudo apt-get install gtkwave</br>

![Screenshot from 2024-02-21 22-42-29](https://github.com/HemaPriyaMudium/VSDSquadron-mini/assets/160724714/c23067b7-4da1-4e8f-ac8f-26965f553aad)
