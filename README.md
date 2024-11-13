<h3 align="center">C Compiler</h3>

<div align="center">
A C compiler with a React-based user interface, utilizing Flex and Bison for lexical analysis and parsing. This compiler enables users to write, compile and execute C code, with a clear visual breakdown of each compilation stage. From tokenization tables and compilation status to intermediate code and final output, this tool is ideal for both learners and developers seeking a detailed look at the compilation process.
</div>

<details>
  <summary>Contents</summary>
  <ol>
    <li><a href="#about">About</a>
        <ul>
          <li><a href="#built-with">Built With</a></li>
          <li><a href="#phases-and-technologies">Phases and Technologies</a></li>
        </ul>
    </li>
    <li><a href="#getting-started">Getting Started</a>
        <ul>
          <li><a href="#prerequisites">Prerequisites</a></li>
          <li><a href="#installation">Installation</a></li>
        </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
  </ol>
</details>

---

## About

This C compiler with React UI provides an interactive experience for exploring each phase of C compilation, from tokenization to assembly code generation. Bison, an LALR (Look-Ahead LR) parser, processes syntax rules, while Flex handles lexical analysis. This compiler runs on Linux systems (e.g., Ubuntu), making it a comprehensive tool for learning or teaching C programming.

### Built With

- [![React](https://skillicons.dev/icons?i=react&perline=3)](https://skillicons.dev) **React.js** – User Interface
- [![Node](https://skillicons.dev/icons?i=nodejs&perline=3)](https://skillicons.dev) **Node.js** – Backend Server
- [![Express](https://skillicons.dev/icons?i=express&perline=3)](https://skillicons.dev) **Express.js** – REST API
- [![Linux](https://skillicons.dev/icons?i=linux&perline=3)](https://skillicons.dev) **Linux** – Development Environment
- [![Bash](https://skillicons.dev/icons?i=bash&perline=3)](https://skillicons.dev) **Bash/Shell** – Scripting and Automation

Additional tools and libraries:
- **Lex & Flex** – Tokenizes the source code
- **Bison** – LALR parser for grammar and syntax analysis
- **Node.js Child Processes** – Manages code compilation processes
- **File Handling** – Manages code input/output

### Phases and Technologies

| Phase               | Description                                                   | Tools/Technologies Used           |
|---------------------|---------------------------------------------------------------|-----------------------------------|
| Lexical Analysis    | Tokenizes source code into identifiable symbols               | Lex, Flex                         |
| Syntax Analysis     | Analyzes token structure and enforces grammar rules           | Bison (LALR Parser)               |
| Semantic Analysis   | Ensures variables and functions are used correctly            |  C Validation Logic               |
| Intermediate Code   | Generates an intermediate representation of the code          | Node.js                           |
| Optimization        | Enhances code efficiency through optimization techniques      | Custom Node.js Scripts            |
| Code Generation     | Translates intermediate code into assembly/machine code       | Node.js Child Processes, Linux    |
| Error Handling      | Captures and displays syntax and semantic errors              | Bison, Node.js                    |

---

## Getting Started

### Prerequisites

To use this compiler, your system must include:
- **Linux** (e.g., Ubuntu) as the development environment
- **Node.js** (v17.0.0 LTS or above)
  ```sh
  # Install Node.js (if not already installed)
  Download and install Node.js v17.0.0 LTS or later
  ```
- **npm** (Latest version)
  ```sh
  npm install npm@latest -g
  ```
- **React** (via npm) installed on your system
```sh
npm install react
```

### Installation

Follow these steps to set up the project.

1. **Clone the Repository**
   ```sh
   git clone https://github.com/AtharvaKulkarniIT/C-Compiler.git
   ```

2. **Install Frontend Dependencies**
   ```sh
   cd Frontend
   npm install --force
   ```

3. **Install Backend Dependencies**
   ```sh
   cd Backend
   npm install --force
   ```

4. **Install Flex and Bison**
   ```sh
   sudo apt-get update
   sudo apt-get install flex bison
   ```

5. **Run the Frontend**
   ```sh
   cd Frontend
   npm run start
   ```

6. **Run the Backend**
   ```sh
   cd Backend
   nodemon Server.js
   ```

7. **You're ready!**
   Enter C code into the editor, run the compiler and watch each phase visualized step-by-step.

---

## Usage

Enter your C code in the editor, initiate the compiler and view each phase from tokenization to assembly generation, gaining insights into the compiler’s functionality and structure.
