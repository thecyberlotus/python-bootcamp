
# 🐍 Pip Quick Reference  

### 🔧 Basics  
```bash
pip install package         # 📦 Install package
pip install package==1.2.3  # 📌 Install specific version
pip uninstall package       # ❌ Remove package
pip show package            # ℹ️ Info on installed package
```

### 📦 Requirements  
```bash
pip freeze > requirements.txt   # 📝 Save current env
pip install -r requirements.txt # 📥 Install from file
```

### ✅ Checks  
```bash
pip list         # 📃 Show installed packages
pip check        # 🔍 Check for dependency issues
pip --version    # 🔢 Confirm pip version
```

### ⏫ Upgrade  
```bash
pip install --upgrade pip        # ⬆️ Upgrade pip itself
pip install --upgrade package    # ⬆️ Upgrade a package
```

### 🌍 Global vs venv  
```bash
which pip     # 🗺️ Show which pip is active
which python  # 🐍 Confirm linked Python
```
*(Should point to `.venv/...` when venv is active.)*  
