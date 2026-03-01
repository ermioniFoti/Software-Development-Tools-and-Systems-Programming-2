# Linux Commands, Bash Scripting & Process Programming

A specialized systems programming project focused on Linux environment mastery, shell automation, and concurrent process management. This project was developed as **Assignment 2** for the **Software Development Tools & Systems Programming (PLH 211)** course at the **Technical University of Crete** (Winter 2024).

## 📌 Project Overview
The objective of this project is to gain practical experience with the Linux command-line interface, automate complex workflows using Bash scripting, and implement multi-process applications in Python using system calls and inter-process communication.

## 🚀 Key Components

### 1. Linux Command Line Exploration
Utilization of core Linux utilities to perform complex data filtering and system analysis tasks.
* **Data Mining:** Using `grep`, `awk`, `sed`, and `sort` to extract specific patterns from large datasets.
* **System Monitoring:** Leveraging commands like `ps`, `top`, `lscpu`, and `df` to analyze hardware utilization and active processes.

### 2. Bash Shell Scripting
Development of robust automation scripts to handle file management and text processing.
* **Sentiment Analysis Script:** A Bash script that iterates through text data, compares tokens against a "positive stems" library, and calculates sentiment scores.
* **Log Rotation & Maintenance:** Scripts designed to manage application logs and organize dataset files dynamically.

### 3. Process Programming (Python)
Implementation of concurrent execution models to optimize performance and handle asynchronous tasks.
* **Process Creation:** Using the `multiprocessing` module and `os.fork()` to create child processes.
* **Inter-Process Communication (IPC):** Coordinating tasks between processes using Pipes and Queues.
* **Synchronization:** Implementing mechanisms to prevent race conditions during shared resource access.
* **Parallel Execution:** Distributing heavy computational tasks across multiple CPU cores to measure execution speedup.

## 🛠️ Technical Specifications
* **Languages:** Bash (Shell Scripting), Python 3.
* **Platform:** Developed and tested on **Google Colab** (Linux environment).
* **Core Concepts:** Process IDs (PID), Parent-Child relationships, Shell redirection, Pipes, and Signal handling.

## 📂 Project Structure
* `positive_stems.txt`: A library of word stems used for sentiment analysis.
* `bash_scripts/`: Collection of `.sh` files for automation tasks.
* `process_mgmt/`: Python scripts demonstrating process forking and IPC.
* `PLH211_Project2_2024_2025.ipynb`: The main notebook containing the full implementation and experimental results.

---
*Developed for the School of Electrical and Computer Engineering, Technical University of Crete.*
