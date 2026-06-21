# 💻 Operating System (OS)

Welcome to my repository for the Operating Systems course (`SECR2043`). This space serves as a portfolio of my system-level programming journey, command-line proficiency, and core hardware-software interaction experiments using Linux and C.

---

## 📖 Course Overview
This course explores the architecture, mechanisms, and internal logic that allow operating systems to manage hardware resources efficiently. Through extensive hands-on laboratory work and system simulation projects, I investigated the critical concepts that keep systems secure, stable, and fast. 

Key themes include command-line shell environments, low-level process creation, thread hierarchy, resource optimization, access control permissions, and address mapping strategies.

---

## 📂 Repository Structure & Project Breakdown

### 🔹 Course Project
* **Memory Management Simulation (`/SECR2043_Project_GroupPING_Paging.pdf`)**: A collaborative simulation project implementing a logical-to-physical address translation engine using the paging technique, framed creatively around a real-world Netflix infrastructure scenario. Written in C, the system visually maps logical pages to physical frames, demonstrating how an OS completely avoids memory fragmentation.

### 🔹 Lab Assessments
* **Lab 1: Basic Linux Commands (`/Lab Assessment 1 Farra.pdf`)**: Foundation work focusing on terminal interaction, environment control, user space exploration, and automating multi-argument string utilities written and compiled via `gcc` inside raw Linux shells.
* **Lab 2: Linux Process Monitoring & Management (`/Lab Assessment 2 Farra.pdf`)**: Deep dive into tracking concurrent process workloads. Tasks included monitoring process states using `ps`, diagnosing application dependencies via tree hierarchies, tweaking task scheduling properties using `renice`, and implementing multi-threaded script executions.
* **Lab 3: File Management & Shell Scripting (`/Lab Assessment 3 Farra.pdf`)**: Automation and safety configuration. This assessment highlights writing robust Bash shell scripts (`.sh`) to recursively create files and structuring strict file access configurations via octal token overrides (`chmod`) to enforce Owner, Group, and Public domain permissions.

---

## 🛠️ Tech Stack & Concepts Covered
* **Environments & Languages:** Linux Bash Shell, C/C++
* **Utilities:** `gcc`, `nano`, `wget`, system architecture tools (`ps`, `pstree`, `pkill`, `renice`)
* **Concepts:** System Calls, Multiprocessing, Resource Priority Management, File System Trees, Access Control Lists (ACLs), and Page Table Mappings.

---

## 💡 Course Reflection & Personal Key Takeaways

### 🧠 Intellectual Growth
This course shattered the illusion that code runs in a vacuum. Before taking this class, I took hardware interaction for granted. Building shell scripts and watching background threads map out into parent-child trees taught me exactly how much coordination it takes to keep programs executing smoothly without crashing the hardware. It forced me to start evaluating software not just by its logical output, but by its overall resource footprint and execution safety.

### 🛑 Biggest Challenge Overcome
Adapting to process management mechanisms and mapping pointer states in memory translation was incredibly taxing. Encountering deadlocks, tracking unmapped memory pointers during data manipulation, and dealing with permission barriers while configuring the local environment required extensive paper-tracing. Learning to break down complex system behaviors via terminal logging and step-by-step diagnostic utilities built immense resilience into my runtime debugging process.

### 🌟 Most Rewarding Project
Developing the **Netflix Scenario Paging Simulator**. Taking a complex concept like logical address spaces, physical frame tables, and translation lookups and modeling them into a tangible consumer application simulation was deeply satisfying. It bridged the gap between abstract textbook theories and concrete architecture execution, solidifying my ambition to build highly efficient, hardware-aware computer systems.
