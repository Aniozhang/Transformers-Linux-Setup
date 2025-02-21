# "LLM-Env-Guide" 🤖
In this hand-on project, we will be dicussing about how we can fine tune LLAMA 2 model with custom dataset using parameter efficient Transfer Learning  using LoRA :Low-Rank Adaptation of Large Language Models.

# 🚀 Setting Up a Virtual Environment in Linux for Transformer Training

This guide will help you create a **Python virtual environment** in **Linux**, install required dependencies, and run a Transformer model training script.

---

## 📢 **Prerequisites**
Before you begin, ensure you have:
- **Linux** (Ubuntu/Debian recommended)
- **Python 3.8+**
- **pip** installed

---

## 📌 **Step 1: Install Python and Virtual Environment**
First, update your package list and install Python with `venv`:
```sh
sudo apt update
sudo apt install python3 python3-venv python3-pip -y

---

## 📌 **Step 2: Create a Virtual Environment**
Navigate to your project directory:
```sh
cd /path/to/your/project
Create a virtual environment named venv:
```sh
python3 -m venv venv

---

## 📌 **Step 3: Activate the Virtual Environment**
For Ubuntu/Linux (Bash, Zsh, Fish shells):
```sh
source venv/bin/activate

# 🚀 You're all set! Now run your Transformer training script! 🎉
