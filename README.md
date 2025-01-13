# RISC-V Internship program powered by SAMSUNG and VSD
This RISC-V Internship using VSDSquadron Mini is based on RISC-V architecture and uses open-source tools to teach students about VLSI SoC Design and RISC-V. The instructor and guide for this internship is Kunal Ghosh Sir, Founder of VSD.

## Personal Details
- **Name**: Arkaprova Mitra
- **College**: R V Institute of Technology and Management
- **Email ID**: rvit22bec017.rvitm@rvei.edu.in
- **GitHub Profile**: [A-R-K-O](https://github.com/A-R-K-O)
- **LinkedIn Profile**: [Arkaprova Mitra](https://www.linkedin.com/in/arkaprova-mitra)

## Tasks
<details>
  <summary>Task 1</summary>
  
  ### Task 1
  *Cbased lab screenshots*
  

  ## Photos
  ### Photo 1
To calculate the sum of numbers within any user-defined range using the RISC-V toolchain on Ubuntu, you can write an assembly program that allows you to set the starting (`t0`) and ending (`t1`) values dynamically. The program begins by initializing two registers with the start and end values of the range. A loop is then implemented to iteratively add each number within the range to an accumulator register (`t2`). At each step, the starting value is incremented until it exceeds the end value. The sum is stored in a designated register (`a0`), which can later be used for verification or further processing. This flexibility enables you to calculate the sum of any range of numbers by simply modifying the initialization values. After writing the code (e.g., `dynamic_sum.s`), it is assembled into an object file using the `riscv64-linux-gnu-as` assembler and then linked to create an executable using `riscv64-linux-gnu-ld`. The program is executed with an emulator like QEMU, which simulates RISC-V architecture on non-RISC-V hardware. This approach demonstrates a dynamic and customizable solution for summing numbers using the RISC-V assembly toolchain.
  ![c based](https://github.com/user-attachments/assets/2a126973-2cc3-4e92-9924-f2f890ce7454)

  
  ### Task 1
  *RISC-V based lab screenshots*
  ### Photo 2
  ![Description of Photo 2](path/to/photo2.jpg)
</details>
