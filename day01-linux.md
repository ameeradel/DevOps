# Day 01 – Linux Essentials & Bash Scripting

## ✅ Goals
- Refresh Linux command-line essentials
- Learn basic Bash scripting (variables, conditionals, loops, functions)

---

## 🐧 Linux Essentials

### 🔹 Navigation & Files
- `pwd`, `ls -l`, `cd`, `touch`, `mkdir`, `rm`, `mv`, `cp`
- Hidden files: `ls -a`
- Recursive: `mkdir -p`, `rm -r`

### 🔹 Permissions & Ownership
- `chmod`, `chown`
- Modes: `755`, `u+x`, etc.

### 🔹 Users & Processes
- `whoami`, `id`, `adduser`, `usermod`
- `ps`, `top`, `kill`, `htop`

---

## 💻 Bash Scripting

### 🔸 Basics
```bash
#!/bin/bash
echo "Hello, Ameer!"
```

### 🔸 Variables & Input
```bash
name="Ameer"
read -p "Enter your age: " age
```

### 🔸 Conditionals
```bash
if [ $age -ge 18 ]; then
  echo "Allowed"
else
  echo "Underage"
fi
```

### 🔸 Loops
```bash
for i in {1..5}; do
  echo "Line $i"
done
```

### 🔸 Functions
```bash
greet() {
  echo "Hello, $1"
}
greet "Salma"
```

---

## 🔧 Hands-on Practice
- Wrote scripts to check user age, loop lines, and greet users
- Learned about positional parameters like `$1`, `$@`

---

## 🎯 Completed
- ✅ Linux refresher (navigation, permissions, users)
- ✅ Bash basics (scripts, input, logic, loops)
- ✅ Troubleshooting with file names and permissions