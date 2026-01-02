#  GEAR-DOS Terminal Emulator

A retro-styled, browser-based DOS terminal simulation built with **HTML, CSS, and Vanilla JavaScript**.  
**GEAR-DOS** features a custom boot sequence, a functional virtual file system, and a built-in Python-style shell.

---

## 🚀 Features

- **Boot Animation**  
  Simulates a vintage system startup with delayed loading messages.

- **Virtual File System**  
  Supports creating directories, navigating paths, and writing/deleting files within the session memory.

- **Dynamic Command Prompt**  
  The prompt (`C:\>`) updates dynamically as you navigate folders.

- **Mini Python Shell (PYS)**  
  Includes a PYS mode for evaluating JavaScript expressions in a Python-like environment.

- **Responsive UI**  
  Classic green-on-black “Matrix” aesthetic using monospace fonts.

---

## 🛠️ Command Reference

| Command | Description | Usage |
|-------|------------|-------|
| `CLS` | Clears the terminal screen | `CLS` |
| `MD` | Makes a new directory | `MD [folder_name]` |
| `RD` | Removes an existing directory | `RD [folder_name]` |
| `CD` | Changes current directory (`..` to go back) | `CD [folder_name]` |
| `DIR` | Lists all files and folders in current path | `DIR` |
| `CT` | Create Text: Create a file and enter write mode | `CT [filename.txt]` |
| `TYPE` | Displays the content of a file | `TYPE [filename.txt]` |
| `DEL` | Deletes a file | `DEL [filename.txt]` |
| `COPY` | Copies a file to a new destination | `COPY [source] [destination]` |
| `REN` | Renames a file | `REN [old_name] [new_name]` |
| `DATE` | Displays the current system date | `DATE` |
| `TIME` | Displays the current system time | `TIME` |
| `PYS` | Enters the Mini Python Shell mode | `PYS` |
| `HELP` | Lists all available commands | `HELP` |

---

##  How to Use

### 🔹 Boot Up
1. Open the HTML file in any modern web browser.
2. Wait **~9 seconds** for the **GEAR-OS initialization** to complete.

---

### 📁 File Management

- Use MD Projects to create a folder.

- Use CD Projects to enter it.

- Use CT note.txt to start writing. Type your text, then type SAVE on a new line to finish.

# Python Mode:

- Type PYS to enter the shell.

- Perform math or JS logic (e.g., 5 * 5 or Math.PI).

- Type exit to return to standard DOS mode.
---
## 📝 Technical Details
# Safety:
- The Python shell uses a wrapped eval() function (note: for simulation purposes only).

# Persistence: 
- This is a client-side simulation; refreshing the page will reset the virtual file system.
