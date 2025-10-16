# Beautiful-power-shell-

# 🖥️ Custom PowerShell Prompt — Oh-My-Posh Style

This script customizes your PowerShell prompt with **Powerline-style segments**, **icons**, and **color transitions**, similar to popular themes like **Oh-My-Posh**, but implemented purely in PowerShell — no external dependencies!

---

## ✨ Features

- 🧑‍💻 Displays your **username**
- 📂 Shows the **current working directory** (with clickable path support)
- 🌿 Detects and displays the current **Git branch**
- 🎨 Smooth Powerline-style **curved separators**
- 💡 Uses **Unicode icons** (requires Nerd Font)
- ✅ Shows a clean success indicator at the end of the line


## ⚙️ Setup

1. **Install a Nerd Font**
   - Download and install [MesloLGS NF](https://www.nerdfonts.com/font-downloads) (recommended).
   - In VS Code or Windows Terminal, set:
     ```
     Settings → Terminal → Font Family → "MesloLGS NF"
     ```

2. **Add the Script to Your PowerShell Profile**

   Open your PowerShell profile:
   ```powershell
   notepad $PROFILE // code $profile

3. copy the file from the powershellfile to $profile
  
