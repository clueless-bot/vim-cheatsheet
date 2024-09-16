## Vim Commands Cheat Sheet

### **Basic Modes**
- **Insert Mode**: Type `i` to enter insert mode.
- **Exit Insert Mode**: Press `ESCAPE`
- **Save and Quit**: Type `:wq`
- **Quit Without Saving**: Type `:q!`

### **Searching**
- **Search Forward**: Type `/keyword_to_find` and press `Enter`
- **Search Backward**: Type `?keyword_to_find` and press `Enter`
- **Next Match**: Press `n`
- **Previous Match**: Press `N`
- **Search Current Word Forward**: Press `*`
- **Search Current Word Backward**: Press `#`

### **Replacing**
- **Global Replace**: Type `:%s/WordToReplace/ReplacedWord/g`

### **Inserting Text**
- **Insert at Start of Line**: Press `SHIFT + i`
- **Insert on New Line Below**: Press `o`.
- **Insert on New Line Above**: Press `SHIFT + o`

### **Editing**
- **Delete Character in Normal Mode**: Press `x`
- **Replace Single Character**: Press `r` followed by the new character
- **Delete Entire Line**: Press `dd`
- **Cut Multiple Lines**: Keep pressing `d`
- **Delete Specific Number of Lines**: Type the number (e.g., `15`) followed by `dd`

### **Undo/Redo**
- **Undo Last Change**: Press `u`
- **Redo Last Undo**: Press `CTRL + r`
- **Undo All Changes**: Type `:e!`

### **Copying and Pasting**
- **Paste Below Cursor**: Press `p`
- **Paste Above Cursor**: Press `SHIFT + p`
- **Copy Line**: Press `SHIFT + v`, then press `y` to yank (copy).
- **Copy Character or Selection**:
  - Single Character: Press `v`, then press `y`
  - Select Text with Visual Mode (`v`), then press `y`

### **Line Numbers and Syntax Highlighting**
- **Enable Line Numbers**: Type `:set nu`
- **Disable Line Numbers**: Type `:set nonu`
- **Disable Syntax Highlighting**: Type `:syntax off`
- **Enable Syntax Highlighting**: Type `:syntax on`

### **Navigation**
- **Go to Top of File**: Press `gg`
- **Go to Specific Line Number**: Type `:<line_number>`, e.g., `:22`

### **Multiple Files and File Comparison**
- **Open Multiple Files Horizontally Split**: Type `vim -o file1 file2`
- **Switch Between Files in Split View**: Press `CTRL + ww`
- **Compare Files (Diff Mode)**: Type `vim -d file1 file2`
