# 🚀 CLI_js Installation Guide

Follow the steps below to set up and test the CLI tool.

---

## 📦 1. Clone the Repository

Clone the CLI_js repository from GitHub:

```bash
git clone https://github.com/malhotraarshdeepsingh/CLI_js
```

## 🛠 2. Set Up the Tool

Navigate to the tool directory, install dependencies, and link the tool globally:

```bash
cd CLI_js/tool
npm i
npm link
```

## 🧪 3. Integrate with testProject

Now, move into the testProject directory, install its dependencies, and link the tool locally.

```bash
cd ../testProject
npm i
npm link tool
```

## 🚩 4. Run the Tool

Once everything is set up, you can start the CLI tool using the following command:

```bash 
tool --start
```
