# TypeScript Directory

This directory contains a comprehensive TypeScript learning project that covers fundamental to advanced concepts in TypeScript development.

## 📋 About This Directory

This TypeScript directory is part of the Holberton School web development curriculum, specifically focusing on TypeScript fundamentals and advanced concepts. The project is structured to provide progressive learning through hands-on tasks.

**Project Details:**

- **Author:** Johann Kerbrat, Engineering Manager at Uber Works
- **Skill Level:** Amateur
- **Weight:** 1
- **Manual QA Review Required**

## 🎯 Learning Objectives

Upon completion of this directory, you will understand and be able to implement:

- **Basic TypeScript Types** - Primitives, arrays, objects
- **Interfaces & Classes** - Object-oriented programming in TypeScript
- **DOM Manipulation** - Working with the Document Object Model using TypeScript
- **Generic Types** - Creating reusable, type-safe components
- **Namespaces** - Organizing code and avoiding naming conflicts
- **Declaration Merging** - Extending existing interfaces and types
- **Ambient Namespaces** - Importing and typing external JavaScript libraries
- **Nominal Typing** - Creating distinct types for type safety

## 📚 Prerequisites & Resources

**Required Reading:**

- [TypeScript in 5 minutes](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html)
- [TypeScript Documentation](https://www.typescriptlang.org/docs/)
- [TypeScript DOM Manipulation Guide](https://www.typescriptlang.org/docs/handbook/dom-manipulation.html)
- [TypeScript Object Types](https://www.typescriptlang.org/docs/handbook/2/objects.html)
- [TSConfig Reference](https://www.typescriptlang.org/tsconfig)

## 🗂️ Directory Structure

```
TypeScript/
├── task_0/                     # Student Interface & DOM Manipulation
│   ├── js/main.ts
│   ├── package.json
│   ├── tsconfig.json
│   ├── webpack.config.js
│   └── .eslintrc.js
├── task_1/                     # Teacher Interface & Class Implementation
│   ├── js/main.ts
│   ├── package.json
│   ├── tsconfig.json
│   └── webpack.config.js
├── task_2/                     # Advanced Types & Employee Management
│   ├── js/main.ts
│   ├── package.json
│   ├── tsconfig.json
│   └── webpack.config.js
├── task_3/                     # Ambient Namespaces & CRUD Operations
│   ├── js/
│   │   ├── main.ts
│   │   ├── interface.ts
│   │   ├── crud.d.ts
│   │   └── crud.js
│   ├── package.json
│   ├── tsconfig.json
│   └── webpack.config.js
├── task_4/                     # Namespaces & Declaration Merging
│   ├── js/subjects/
│   │   ├── Teacher.ts
│   │   ├── Subject.ts
│   │   ├── Cpp.ts
│   │   ├── React.ts
│   │   └── Java.ts
│   ├── package.json
│   └── tsconfig.json
├── task_5/                     # Brand Convention & Nominal Typing
│   ├── js/main.ts
│   ├── package.json
│   ├── tsconfig.json
│   └── webpack.config.js
└── README.md
```

## 📋 Task Overview

### 🔰 Task 0: Creating an Interface for a Student

**Concepts:** Basic interfaces, DOM manipulation

- Create `Student` interface with required properties
- Implement table rendering with vanilla JavaScript
- Practice basic TypeScript syntax and DOM manipulation

### 🔰 Task 1: Let's Build a Teacher Interface

**Concepts:** Advanced interfaces, readonly properties, index signatures

- Create flexible `Teacher` interface with readonly initialization
- Implement property extension capabilities
- Create `Directors` interface extending `Teacher`
- Build `printTeacher` function with interface typing

### 🔰 Task 2: Advanced Types Part 1

**Concepts:** Interface implementation, factory patterns, type predicates

- Implement `DirectorInterface` and `TeacherInterface`
- Create employee factory function with conditional logic
- Build type predicate functions for runtime type checking
- Implement string literal types

### 🔰 Task 3: Ambient Namespaces

**Concepts:** Ambient declarations, external library integration

- Work with external JavaScript library (`crud.js`)
- Create ambient type declarations (`.d.ts` files)
- Implement proper module importing and typing
- Practice triple-slash directives

### 🔰 Task 4: Namespace & Declaration Merging

**Concepts:** Namespaces, declaration merging, modular architecture

- Create subject-based teaching system
- Implement declaration merging for interface extension
- Build modular namespace structure across multiple files
- Practice inheritance and method implementation

### 🔰 Task 5: Brand Convention & Nominal Typing

**Concepts:** Branded types, nominal typing, type safety

- Implement credit system with distinct, non-interchangeable types
- Create branded interfaces for type discrimination
- Build type-safe arithmetic functions

## ⚙️ Technical Requirements

**Development Environment:**

- **Allowed Editors:** vi, vim, emacs, Visual Studio Code
- **Platform:** Ubuntu 18.04 (for transpilation)
- **Testing:** Jest version 24.9.\*
- **File Extensions:** Use `.ts` when possible
- **Line Endings:** All files must end with a new line

**Code Quality:**

- TypeScript compiler must show no warnings or errors
- Every variable should use TypeScript typing when possible
- Follow TypeScript best practices and conventions
- Maintain consistent code formatting

## 🚀 Getting Started

### Prerequisites

- Node.js and npm installed
- Basic understanding of JavaScript
- Familiarity with object-oriented programming concepts

### Setup Instructions

1. **Navigate to the TypeScript directory:**

   ```bash
   cd holbertonschool-web_react/TypeScript
   ```

2. **Choose a task to work on:**

   ```bash
   cd task_0  # Start with task 0
   ```

3. **Install dependencies:**

   ```bash
   npm install
   ```

4. **Start development:**

   ```bash
   npm run start-dev
   ```

5. **Build for production:**

   ```bash
   npm run build
   ```

6. **Validate your work:**
   ```bash
   # Should return "No type errors found"
   npx webpack
   ```

## 🛠️ Configuration Files

Each task includes standard configuration files:

- **`package.json`** - Dependencies, scripts, and project metadata
- **`tsconfig.json`** - TypeScript compiler options and settings
- **`webpack.config.js`** - Module bundling and development server configuration
- **`.eslintrc.js`** - Code linting rules and style enforcement

## ✅ Validation & Testing

**Before Submitting:**

1. Run `npm run build` - Must show no TypeScript errors
2. Verify all requirements are met for each task
3. Test functionality in browser (for DOM manipulation tasks)
4. Ensure code follows TypeScript best practices
5. Request manual QA review when complete

**Common Issues:**

- Missing type annotations
- Incorrect interface implementations
- Webpack build errors
- Missing configuration files

## 🎓 Learning Path

**Recommended Order:**

1. **Task 0** - Get familiar with basic TypeScript syntax
2. **Task 1** - Understand interfaces and advanced typing
3. **Task 2** - Learn about classes and type predicates
4. **Task 3** - Master ambient declarations and external libraries
5. **Task 4** - Explore namespaces and modular architecture
6. **Task 5** - Understand advanced typing patterns

## 💡 Tips for Success

- **Start Simple:** Begin with basic types before moving to complex interfaces
- **Read Error Messages:** TypeScript provides detailed error information
- **Use IDE Features:** Leverage autocomplete and type checking in your editor
- **Practice Incrementally:** Build each task step by step
- **Test Frequently:** Compile often to catch errors early

## 🤝 Getting Help

- Review TypeScript documentation for detailed explanations
- Check task requirements carefully before implementation
- Use TypeScript playground for quick testing
- Consult with peers and instructors for clarification

## 📄 Repository Context

This directory is part of the `holbertonschool-web_react` repository, focusing specifically on TypeScript fundamentals within the broader context of modern web development education.
