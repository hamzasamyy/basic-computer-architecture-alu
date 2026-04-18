# 💻 16-bit Basic Computer Architecture with ALU (Logisim)

## 🚀 Overview
Design and simulation of a 16-bit basic computer system in Logisim featuring a shared bus architecture, registers, memory unit, control logic, and an ALU supporting multiple arithmetic and logical operations.

---

## 📄 Project Report
📥 **Full detailed report available here:**  
👉 [View Project Report](./Computer_Organization_Project_Report.pdf)

The report includes:
- Complete system architecture explanation  
- Bus and memory design  
- Register implementation (AR, PC, DR, AC, IR, TR)  
- ALU design and supported operations  
- Instruction-level execution cycles  
- Testing and validation  

---

## 🧠 Features
- 🧮 16-bit computer system design  
- 🔄 Common bus architecture using multiplexer  
- 🧠 6 registers (AR, PC, DR, AC, IR, TR)  
- 💾 256 × 16-bit memory unit  
- ⚙️ Control logic with clock synchronization  
- ➕ ALU supporting:
  - Addition  
  - Subtraction  
  - Multiplication  
  - Division  
  - Complement  
  - XOR operations  
- 🔁 Instruction cycle execution  

---

## 🛠️ Technologies Used
- Logisim  
- Digital Logic Design  
- Computer Architecture  

---

## 📂 Project Structure

```text
basic-computer-architecture-alu/
│
├── basic_computer.circ                    # Main Logisim circuit
├── Computer_Organization_Project_Report.pdf
├── README.md
```

---

## ▶️ How to Run

1. Download and install Logisim  
2. Open `basic_computer.circ`  
3. Run the simulation using the clock  
4. Observe:
   - Data transfer through the bus  
   - Register operations  
   - ALU computations  
   - Instruction execution cycles  

---

## 🧩 How It Works
- The system uses a **shared 16-bit bus** controlled by selection lines  
- Registers and memory communicate through a **multiplexer-based bus system**  
- The ALU takes inputs from registers and performs operations based on control signals  
- Results are stored back into registers or memory  
- The system simulates low-level instruction execution step by step  

---

## 📸 Demo
(Add a screenshot of your circuit)

```markdown
![Circuit](screenshot.png)
```

---

## 💡 Future Improvements
- 🧠 Full instruction set implementation (ISA)  
- 🔄 Advanced control unit (microprogrammed)  
- ⚡ Pipeline simulation  
- 📊 Visual step-by-step execution tracing  

---

## 👨‍💻 Author
Hamza Muhammad Samy Aly Hassanein  
📧 hamzasamy54@gmail.com  
🔗 https://www.linkedin.com/in/hamza-samy-161a74356  
💻 https://github.com/hamzasamyy  

---

## ⭐ If you like this project
Give it a ⭐ on GitHub!
