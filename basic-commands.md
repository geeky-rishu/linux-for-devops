# Linux Commands Categorized

## 1. **User & System Information:**

- **whoami**:  
  Displays the current logged-in user's username.
  ```bash
  $ whoami
  ```

- **date**:  
  Shows the current system date and time.
  ```bash
  $ date
  ```

- **uptime**:  
  Displays how long the system has been running, along with current time, number of users, and load average.
  ```bash
  $ uptime
  ```

## 2. **File & Directory Operations:**

- **pwd**:  
  Prints the current working directory.
  ```bash
  $ pwd
  ```

- **ls**:  
  Lists files and directories.
  ```bash
  $ ls
  ```

- **mkdir**:  
  Creates a new directory.
  ```bash
  $ mkdir new_directory
  ```

- **touch**:  
  Creates an empty file or updates the timestamp of an existing file.
  ```bash
  $ touch file.txt
  ```

- **cat**:  
  Concatenates and displays file contents.
  ```bash
  $ cat file.txt
  ```

- **head**:  
  Shows the first 10 lines of a file by default.
  ```bash
  $ head file.txt
  ```

- **tail**:  
  Shows the last 10 lines of a file by default.
  ```bash
  $ tail file.txt
  ```

## 3. **Navigation Commands:**

- **cd**:  
  Changes the current directory.
  ```bash
  $ cd /path/to/directory
  ```

- **cd /**:  
  Navigates to the root directory.
  ```bash
  $ cd /
  ```

- cd ~:  
  Navigates to the home directory.
  ```bash
  $ cd ~
  ```

## 4. **Terminal & Utility Operations:**

- **clear**:  
  Clears the terminal screen.
  ```bash
  $ clear
  ```

- **echo**:  
  Prints text to the terminal or writes it to a file.
  ```bash
  $ echo "Hello World"
  ```

## 5. **Help & Manual:**

- **man**:  
  Displays the manual page for a given command.
  ```bash
  $ man <command>
  ```

## VIM Editor Commands:

- **vim**: To open a file in vim.
  ```bash
  $ vim filename
  ```
- **i**: Enter insert mode to edit text.
- **Esc**: Exit insert mode and return to normal mode.
- **:w**: Save the file.
- **:q**: Quit VIM.
- **dd**: Delete the current line.
- **yy**: Copy (yank) the current line.
- **p**: Paste the yanked content.
- **u**: Undo the last change.
- **/search_term**: Search for a specific term.
- **gg**: Go to the start of the file.
- **G**: Go to the end of the file.

## **sudo and apt** Commands:

- **sudo**: Allows running commands as a superuser.
  ```bash
  $ sudo <command>
  ```

- **apt update**: Updates the package list.
  ```bash
  $ sudo apt update
  ```

- **apt upgrade**: Upgrades all installed packages.
  ```bash
  $ sudo apt upgrade
  ```

- **apt install**: Installs a package.
  ```bash
  $ sudo apt install package_name
  ```

- **apt remove**: Removes a package.
  ```bash
  $ sudo apt remove package_name
  ```

## Additional Syntax for **echo**, **cat**, **head**, and **tail** Commands

### **echo** Command:

- **Basic Usage**:  
  Prints the specified text to the terminal.
  ```bash
  $ echo "Hello World"
  ```

- **Redirect Output to a File**:  
  Writes the text to a file.
  ```bash
  $ echo "This is a test" > file.txt
  ```

- **Append Text to a File**:  
  Adds text to the end of a file.
  ```bash
  $ echo "Additional line" >> file.txt
  ```


---

### **cat** Command:

- **Concatenate and Display Multiple Files**:  
  Display the contents of two or more files sequentially.
  ```bash
  $ cat file1.txt file2.txt
  ```

- **Redirect Output to Another File**:  
  Combine files and write the result to a new file.
  ```bash
  $ cat file1.txt file2.txt > combined.txt
  ```

- **Show Line Numbers**:  
  Display the content of a file along with line numbers.
  ```bash
  $ cat -n file.txt
  ```

- **Create a New File with Cat**:  
  Use cat to create and write into a new file.
  ```bash
  $ cat > newfile.txt
  This is a new file.
  (Ctrl + D to save)
  ```

---

### **head** Command:

- **Display the First N Lines of a File**:  
  Show the first 20 lines of a file.
  ```bash
  $ head -n 20 file.txt
  ```

- **Show the First N Bytes of a File**:  
  Display the first 50 bytes of a file.
  ```bash
  $ head -c 50 file.txt
  ```

---

### **tail** Command:

- **Display the Last N Lines of a File**:  
  Show the last 15 lines of a file.
  ```bash
  $ tail -n 15 file.txt
  ```

- **Show the Last N Bytes of a File**:  
  Display the last 30 bytes of a file.
  ```bash
  $ tail -c 30 file.txt
  ```

