# 💻 Simple-As-Possible (SAP-1) 8-bit Computer Using Proteus

This project is an implementation of the **SAP-1 (Simple As Possible)** 8-bit computer architecture using Proteus. It showcases the fundamental workings of a computer, including a processing unit, control unit, and memory unit, built using discrete components. This project serves as a foundational step for understanding more intricate computer architectures.

**[Project Manual](https://github.com/touhidulislam1999/Simple-As-Possible-SAP-8-bit-computer-using-Proteus/blob/main/SAP%20Project%20Manual.pdf)**

---

## 📜 **Project Overview**
**SAP** stands for "Simple As Possible." Originally introduced by **Albert Paul Malvino** and **Jerald A. Brown**, the SAP architecture lays the groundwork for modern computer fundamentals.  
The architecture includes:
1. **Processing Unit**: Performs arithmetic and logical operations.
2. **Control Unit**: Manages the execution of instructions.
3. **Memory Unit**: Stores data and instructions.

Three types of SAP architectures exist: **SAP-1**, **SAP-2**, and **SAP-3**. This project focuses on SAP-1, designed as a basic yet powerful computer model.

![Custom SAP-1](https://github.com/touhidulislam1999/Simple-As-Possible-SAP-8-bit-computer-using-Proteus/assets/97190512/f910d98d-06e7-4b29-bac1-4e57aa433802)

---

## 🏗️ **Architecture of SAP-1**

### Key Features:
1. **8-bit Bus**
   - Facilitates data transfer within the system.
   - [Video: Explanation of 8-bit Bus](https://youtu.be/dWdzywzoWck?si=vOc8VBNcO41z5CF-)

2. **16x8-bit RAM**
   - Stores instructions and data.
   - [Video: 16x8-bit RAM Design](https://www.youtube.com/watch?v=dWdzywzoWck&list=PLk4sSigu0N0W4v755N_O6Jk1WWrfWIGgm&index=6)

3. **4-bit Program Counter (PC)**
   - Keeps track of the instruction address.
   - [Video: Program Counter Design](https://www.youtube.com/watch?v=SFzbYKfyu8w&list=PLk4sSigu0N0W4v755N_O6Jk1WWrfWIGgm&index=3)

4. **Input Unit and Memory Address Register (MAR)**
   - MAR selects memory locations for instruction fetching.
   - [Video: MAR Design](https://www.youtube.com/watch?v=DHD99TvLEVA&list=PLk4sSigu0N0W4v755N_O6Jk1WWrfWIGgm&index=2)

5. **8-bit Arithmetic Logic Unit (ALU)**
   - Performs arithmetic and logical operations.
   - [Video: ALU Design](https://www.youtube.com/watch?v=jLDd3z0XFQw&list=PLk4sSigu0N0W4v755N_O6Jk1WWrfWIGgm&index=11)

6. **Accumulator (Register A) and Register B**
   - Temporarily stores data for computations.
   - [Video: Accumulator and Register B Design](https://www.youtube.com/watch?v=WmYglyEPKCw&list=PLk4sSigu0N0W4v755N_O6Jk1WWrfWIGgm&index=8)

7. **Clock**
   - Synchronizes operations within the system.
   - [Video: Clock Design](https://www.youtube.com/watch?v=XizNo5aafIs&list=PLk4sSigu0N0W4v755N_O6Jk1WWrfWIGgm&index=4)

8. **3-Bit BCD Display**
   - Converts binary output to BCD for readability.
   - [Video: BCD Display Design](https://www.youtube.com/watch?v=V7LNtxWiSOc&list=PLk4sSigu0N0W4v755N_O6Jk1WWrfWIGgm&index=12)

9. **Control Sequencer**
   - Generates control signals for executing instructions.
   - [Video: Control Sequencer Design](https://www.youtube.com/watch?v=iVXcBfx2rIM&list=PLk4sSigu0N0W4v755N_O6Jk1WWrfWIGgm&index=9)

10. **Instruction Register**
    - Holds the current instruction for decoding and execution.
    - [Video: Instruction Register Design](https://www.youtube.com/watch?v=ychcl_FOTmM&list=PLk4sSigu0N0W4v755N_O6Jk1WWrfWIGgm&index=7)

11. **Address Selector**
    - Determines the next instruction address.
    - [Video: Address Selector Design](https://www.youtube.com/watch?v=X5iI_aPhi5c&list=PLk4sSigu0N0W4v755N_O6Jk1WWrfWIGgm&index=5)

---

## 🔍 **Project Testing**
The system's functionality was tested using Proteus simulations.
- [Video: Project Testing](https://www.youtube.com/watch?v=kuD-TO59JPA&list=PLk4sSigu0N0W4v755N_O6Jk1WWrfWIGgm&index=13)

![Custom SAP-1](https://github.com/touhidulislam1999/Simple-As-Possible-SAP-8-bit-computer-using-Proteus/assets/97190512/f249a9df-d2e8-412b-b63b-1a6185b33dc6)

---

## ✨ **Special Features**
1. **T-State Reduction**:
   - Reduced the T-states from 6 to 4 for improved performance.
2. **Binary to BCD Display**:
   - Added an 8-bit binary to 3-bit BCD converter for better readability.
3. **Negative Number Handling**:
   - Displays a minus (`-`) sign for subtraction when the result is negative.

---

## **Contributor**
**[Faiaz Zahin](https://github.com/fzn011)**
**[Abrar Fahim Saraz](https://github.com/abrarfahimsaraz)**

---

## 🛠️ **How to Use**
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/touhidulislam1999/Simple-As-Possible-SAP-8-bit-computer-using-Proteus.git
