# **MiniShell**  

## 📌 **Description**  
Minishell is a simple shell program inspired by **Bash**. It replicates key functionalities of a shell, including command execution, piping, and signal handling.  

<img width="1025" alt="Image" src="https://github.com/user-attachments/assets/a437d0e9-f16b-45eb-9513-20ada7a82a9d" />

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

## 🙌 Collaborator
|![임현순](https://avatars.githubusercontent.com/u/66724166)|![구혁모](https://avatars.githubusercontent.com/u/115722373?v=4)|
|:-:|:-:|
|[임현순](https://github.com/Hyun-Soon)|[구혁모](https://github.com/siru02)|