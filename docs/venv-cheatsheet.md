
# 🐍 Python Virtual Environment (venv) Quick Reference  

### 🌱 Create a venv  
```bash
python3 -m venv .venv   # 🌱 Create new venv in .venv folder
```

### 🚀 Activate venv  
```bash
source .venv/bin/activate   # 🚀 Activate venv (Unix/macOS)
. .venv/bin/activate        # 🌀 Shorthand
```
Prompt changes to show: `(.venv)`  

### 🛑 Deactivate venv  
```bash
deactivate   # 🛑 Exit the venv and return to system Python
```

### 🔄 Reactivate venv  
```bash
cd ~/Repos/python-bootcamp
source .venv/bin/activate   # 🔄 Step back into the venv
```

### 📦 Install packages inside venv  
```bash
pip install package          # 📦 Installs into this venv only
pip list                     # 📃 Show installed packages
```

### 📝 Requirements management  
```bash
pip freeze > requirements.txt   # 📝 Save current venv packages
pip install -r requirements.txt # 📥 Reinstall from file
```

### ⚡ Auto-activation with direnv  
1. Install direnv:  
   ```bash
   brew install direnv
   echo 'eval "$(direnv hook zsh)"' >> ~/.zshrc
   ```  
2. In project root:  
   ```bash
   echo 'source .venv/bin/activate' > .envrc
   direnv allow
   ```  
👉 Now your venv auto-activates whenever you `cd` into the repo.  

