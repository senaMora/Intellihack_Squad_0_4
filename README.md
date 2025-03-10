# Stock Price Prediction - Virtual Environment Setup

## 📌 Prerequisites
Ensure you have **Python 3.12** installed. You can check your Python version with:
```bash
python3 --version
```

## 🚀 Setting Up a Virtual Environment
Follow these steps to create and activate a virtual environment:

### **1️⃣ Create the Virtual Environment**
```bash
python3.12 -m venv myenv
```

### **2️⃣ Activate the Virtual Environment**
#### **On macOS/Linux:**
```bash
source myenv/bin/activate
```
#### **On Windows (Command Prompt):**
```bash
myenv\Scripts\activate
```

#### **On Windows (PowerShell):**
```powershell
myenv\Scripts\Activate.ps1
```

## 📦 Install Required Libraries
Once the virtual environment is activated, install dependencies from the `requirements.txt` file:

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

## ✅ Verify Installation
To confirm that all packages are installed, run:
```bash
python -c "import pandas, numpy, matplotlib, sklearn; print('All libraries installed successfully!')"
```

## 🛑 Deactivating the Virtual Environment
When you're done working in the virtual environment, deactivate it by running:
```bash
deactivate
```

---

You're all set! 🚀 Happy coding! 