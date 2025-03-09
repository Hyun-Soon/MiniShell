# **MiniShell**  

## 📌 **Description**  
Minishell is a simple shell program inspired by **Bash**. It replicates key functionalities of a shell, including command execution, piping, and signal handling.  

![Image](https://github.com/user-attachments/assets/55caea95-57e7-4f3c-b819-cfb056ecb56c)

## 📜 **Prerequisites**
To compile and run this program, you'll need:

- A C/C++ compiler (e.g., GCC)
- readline library (e.g., brew install readline)
- Make (optional, for easier compilation)

## ⚙️ **Technologies Used**  
- **Pipe**: Implements inter-process communication.  
- **Signal**: Handles system signals for process control.  
- **fork()**: Creates child processes to execute commands.  

## 🚀 **How to Run**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/Hyun-Soon/MiniShell.git
   cd MiniShell
   ```
2. Compile the project:  
   ```bash
   make
   ```
3. Run the shell:  
   ```bash
   ./minishell
   ```  

## 🛠 **Features**  
- Executes basic shell commands.  
- Supports **pipes (`|`)** for command chaining.  
- Handles **signals** like `Ctrl+C` and `Ctrl+D`.  
- Manages child processes using `fork()`.  