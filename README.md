# Holbertonschool-web_react

This repository contains a comprehensive TypeScript learning project covering fundamental to advanced concepts in TypeScript development.

## 📋 Project Overview

This project is designed to provide hands-on experience with TypeScript, covering essential concepts from basic types to advanced features like namespaces and nominal typing.

## 🎯 Learning Objectives

By the end of this project, you will be able to explain and demonstrate:

- Basic types in TypeScript
- Interfaces, Classes, and functions
- DOM manipulation with TypeScript
- Generic types
- Namespaces and declaration merging
- Ambient namespaces for importing external libraries
- Basic nominal typing with TypeScript

## 📚 Resources

- [TypeScript in 5 minutes](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html)
- [TypeScript Documentation](https://www.typescriptlang.org/docs/)
- [TypeScript DOM Manipulation](https://www.typescriptlang.org/docs/handbook/dom-manipulation.html)
- [TypeScript Object Types](https://www.typescriptlang.org/docs/handbook/2/objects.html)
- [TSConfig Reference](https://www.typescriptlang.org/tsconfig)

## ⚙️ Requirements

- **Allowed editors:** vi, vim, emacs, Visual Studio Code
- All files must end with a new line
- Files will be transpiled on Ubuntu 18.04
- TypeScript scripts will be checked with Jest (version 24.9.\*)
- Code should use the `.ts` extension when possible
- TypeScript compiler should show no warnings or errors

## 🗂️ Project Structure

```
TypeScript/
├── task_0/          # Student interface and DOM manipulation
├── task_1/          # Teacher interface and class implementation
├── task_2/          # Advanced types and employee management
├── task_3/          # Ambient namespaces and CRUD operations
├── task_4/          # Namespaces and declaration merging
├── task_5/          # Brand convention and nominal typing
└── README.md

```

## 📋 Tasks

### Task 0: Creating an Interface for a Student

- Create a `Student` interface with basic properties
- Implement DOM manipulation to display student data in a table
- **Files:** `task_0/js/main.ts`, configuration files

### Task 1: Building a Teacher Interface

- Create extensible `Teacher` interface with readonly properties
- Implement flexible property addition
- Extend interface with `Directors`
- **Files:** `task_1/js/main.ts`, configuration files

### Task 2: Advanced Types Part 1

- Implement `DirectorInterface` and `TeacherInterface`
- Create employee factory function
- Implement type predicates and specific functions
- **Files:** `task_2/js/main.ts`, configuration files

### Task 3: Ambient Namespaces

- Work with external JavaScript libraries
- Create ambient type declarations
- Implement CRUD operations with proper typing
- **Files:** `task_3/js/main.ts`, `task_3/js/interface.ts`, `task_3/js/crud.d.ts`

### Task 4: Namespace & Declaration Merging

- Create subject-based class hierarchy
- Implement declaration merging for interfaces
- Build modular namespace structure
- **Files:** Multiple files in `task_4/js/subjects/`

### Task 5: Brand Convention & Nominal Typing

- Implement branded types for type safety
- Create credit system with distinct types
- Demonstrate nominal typing concepts
- **Files:** `task_5/js/main.ts`, configuration files

## 🚀 Getting Started

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/[username]/holbertonschool-web_react.git
    cd holbertonschool-web_react/TypeScript

    ```

2.  **Navigate to a specific task:**

    ```bash
    cd task_0  # or task_1, task_2, etc.

    ```

3.  **Install dependencies:**

    ```bash
    npm install

    ```

4.  **Build the project:**

    ```bash
    npm run build

    ```

5.  **Run in development mode:**

    ```bash
    npm run start-dev

    ```

## 🛠️ Configuration Files

Each task includes the necessary configuration files:

- `package.json` - Node.js dependencies and scripts
- `tsconfig.json` - TypeScript compiler configuration
- `webpack.config.js` - Webpack bundling configuration
- `.eslintrc.js` - ESLint linting rules

## ✅ Validation

- Run `npm run build` to ensure no TypeScript errors
- All variables should use TypeScript when possible
- Code should follow TypeScript best practices
- Manual QA review required upon completion

## 🏗️ Technologies Used

- **TypeScript** - Primary language
- **Webpack** - Module bundling
- **Jest** - Testing framework
- **ESLint** - Code linting
- **Node.js** - Runtime environment

## 📝 Notes

- Each task builds upon previous concepts
- Focus on understanding TypeScript's type system
- Pay attention to interface design and implementation
- Practice proper error handling and type safety

## 🤝 Contributing

This is a learning project. Feel free to:

- Report issues or bugs
- Suggest improvements
- Share alternative implementations
- Provide feedback on code quality

## 📄 License

This project is part of the Holberton School curriculum and is intended for educational purposes.
