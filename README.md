# 📊 Linear & Integer Programming Solver

This project, developed as part of a Linear Programming module, is a **menu-driven application** designed to solve **Linear Programming (LP)** and **Integer Programming (IP)** models. It also performs **sensitivity analysis** to assess how changes in model parameters affect the optimal solution.

## 🧠 Project Overview

The application is implemented in **C# using .NET** and built as a **Visual Studio solution**. It processes mathematical models from structured input files and uses algorithms such as:

- 🧮 **Primal Simplex Method**
- 🔍 **Cutting Plane Method**
- 💡 **Branch and Bound (BnB)**
- 📈 **Two-Phase Simplex**
- 🧪 **Sensitivity Analysis**

## ⚙️ Features

- 📥 **Read LP/IP model from file**
- 🧾 **Process and convert model into canonical form**
- ✅ **Solve using Primal Simplex algorithm**
- 🧠 **Perform Sensitivity Analysis**
- 📄 **Output solution and analysis to text file**
- 📋 **GUI Support** via `mainForm.cs` for interaction and display

## 💻 Technologies Used

- **C#** (.NET Framework)
- **Visual Studio**
- **WinForms** for GUI
- **File I/O** for reading inputs and writing results

## 📁 File Structure Highlights

- `readInput.cs` – Reads and parses input files
- `PrimalSimplex.cs`, `TwoPhase.cs` – Core solving algorithms
- `Sensitivity.cs`, `Slack.cs`, `Excess.cs` – Support for analysis and model refinement
- `mainForm.cs` – Main GUI entry point
- `Project.sln` – Visual Studio Solution

## 🧑‍💻 Collaboration

This project was built collaboratively as a group assignment, with contributions in algorithm design, input handling, GUI development, and testing.

---

