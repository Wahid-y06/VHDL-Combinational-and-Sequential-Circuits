# VHDL Combinational and Sequential Circuits (TMU – COE328 Lab 4)

This project contains my implementation of several combinational and sequential digital circuits using **VHDL** and **Intel Quartus II**.  
It was completed as part of the **COE328 – Digital Systems** course at **Toronto Metropolitan University (TMU)**.

---

## 🔧 Overview

The project includes four VHDL-based modules:

### ✔️ 1. Multiplexer (MUX)
- Implements a **2:1 multiplexer** (mux.vhd)
- Implements a **4:1 multiplexer using two 2:1 muxes** (muxModified.bdf)

### ✔️ 2. Decoder
- Implements a **2:4 decoder** (decode.vhd)
- Implements a **3:8 decoder using two 2:4 decoders** (decodModified.bdf)

### ✔️ 3. Encoder
- Implements a **4-to-2 encoder** (encod.vhd)

### ✔️ 4. Johnson Counter
- Implements a **3-bit Johnson counter with feedback**
- Cycles through the last 6 digits of the student ID using a 4-bit display output
- Includes waveform/state transition simulations

---

## 📁 Project Structure

# VHDL-Combinational-and-Sequential-Circuits
VHDL implementation of multiplexer, decoder, encoder, and Johnson counter using Quartus II for TMU COE328 Digital Systems Lab 4.
Project 1/
│
├── mux/
│ ├── mux.vhd
│ ├── muxModified.bdf
│ └── simulation/
│
├── decode/
│ ├── decode.vhd
│ ├── decodModified.bdf
│ └── simulation/
│
├── encod/
│ ├── encod.vhd
│ └── simulation/
│
├── johns/
│ ├── johns.vhd
│ ├── johns_tb.vhd
│ └── simulation/
│
├── project_files/
│ ├── *.qpf
│ ├── *.qsf
│
└── README.md


---

## 🛠️ Tools & Technologies

- **VHDL**
- **Intel Quartus II**
- **ModelSim / Waveform simulation**
- **FPGA logic design**
- **Combinational & sequential digital circuits**

---

## 👤 Author

**Wahid_y06 (Yahya)**  
Toronto Metropolitan University (TMU)  
Course: COE328 – Digital Systems  
Semester: Fall 2025

---

## 📜 License

This project is for academic and portfolio purposes only.
