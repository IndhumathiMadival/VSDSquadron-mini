**By Referring to C-based Lab videos and RISC-V-based lab videos**

**Snapshots of the compiled C code and RISC-V**

**Step 1: check whether the leafpad is installed in ur machine by using the commands
leafpad sum1ton.c& (sum1ton.c is the file name)
If the leafpad editor is opened without any errors then type the C code.**
****If the leafpad is not installed in ur machine then install by using the following command**

**sudo snap install leafpad****

****Step 2: Writing the C code in the leafpad editor** using the following command

**leafpad sum1ton.c&**
![Screenshot from 2024-02-27 17-02-04](https://github.com/HemaPriyaMudium/VSDSquadron-mini/assets/160724714/3e56f94b-617f-445e-bd62-7e97c9be5883)

**Step 3: After writing the C code save the editor by Ctrl+s**

**Step 4: Check for the errors by using the following command(compilation step)**

**gcc sum1ton.c**
![Screenshot from 2024-02-27 17-05-46](https://github.com/HemaPriyaMudium/VSDSquadron-mini/assets/160724714/c61d0d54-7520-4dcc-a71f-ee44944ba921)


**Step 5: Check the output by using the command**

**./a.out**
![Screenshot from 2024-02-27 17-07-26](https://github.com/HemaPriyaMudium/VSDSquadron-mini/assets/160724714/1c1452dc-43ec-4fd0-971c-2cd0134edda7)

**The results will be displayed as** 

**Sum of numbers from 1 to 500 is 125250**


********************************************************RISCV Compilation and Execution*****************************************************

**Step 1: View the C Code in the editor window using the following command**

**cat sum1ton.c**
![Screenshot from 2024-02-27 17-08-00](https://github.com/HemaPriyaMudium/VSDSquadron-mini/assets/160724714/5584b38b-f2be-402e-bc48-9391d7dee98b)

**Step 2: Compile the code in riscv using the following command**

**riscv64-unknown-elf-gcc -O1 -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c**
![Screenshot from 2024-02-27 17-08-36](https://github.com/HemaPriyaMudium/VSDSquadron-mini/assets/160724714/3a998dfd-287d-4a31-aeaa-11af5d0a7eb8)


**Step 3: The ls ltr command in Linux is used to list the contents of the current directory in long format, sorted by last modified time in reverse order.**

**use the command**

**ls -ltr sum1ton.c**

![Screenshot from 2024-02-27 17-09-08](https://github.com/HemaPriyaMudium/VSDSquadron-mini/assets/160724714/6a88c833-0f62-40fe-8ca0-6e600cf6c342)


![Screenshot from 2024-02-27 17-11-10](https://github.com/HemaPriyaMudium/VSDSquadron-mini/assets/160724714/f6d77d45-2ab8-4edf-bfdb-fc1de9e3b0d3)

**Search for the Main and check the instructions of the C code execution. It has 15 instructions in the C execution**
![WhatsApp Image 2024-02-27 at 5 14 45 PM](https://github.com/HemaPriyaMudium/VSDSquadron-mini/assets/160724714/773de2bc-1c14-4f8c-951b-e4305537e5cc)

![WhatsApp Image 2024-02-27 at 5 15 06 PM](https://github.com/HemaPriyaMudium/VSDSquadron-mini/assets/160724714/ea82e969-5baa-4db8-9b51-adeb3a098cf9)

**Step 4:**

**riscv64-unknown-elf-gcc -Ofast -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c**

![WhatsApp Image 2024-02-27 at 5 15 41 PM](https://github.com/HemaPriyaMudium/VSDSquadron-mini/assets/160724714/083543d8-7f39-43b1-83e4-302d4cd862c5)

![WhatsApp Image 2024-02-27 at 5 15 54 PM](https://github.com/HemaPriyaMudium/VSDSquadron-mini/assets/160724714/100ab35b-fe8a-48d8-9dac-ee627f854bf1)



