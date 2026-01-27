# Bandit Level 0 to Level 1 Walkthrough | OverTheWire
This lab covers the solution for **OverTheWire Bandit Level 0 to Level 1**.
Bandit is a beginner-friendly Linux wargame that helps understand
SSH, basic Linux commands, and file handling.

This walkthrough is intended for:
- Beginners in Linux
- CEH / cybersecurity students
- Anyone starting OverTheWire Bandit

## Level 0 → Level 1

**Goal:**  
Login to the Bandit server and find the password stored in a file.

**Credentials:**
- Username: bandit0
- Password: bandit0

**SSH Command:**
ssh bandit0@bandit.labs.overthewire.org -p 2220

## Solution Steps
1. Connect to the Bandit server using SSH.
![Bandit Level 0 Screenshot](./screenshots/b01.png)

3. After login, list files in the home directory.
  ls
4. A file named `readme` is present.
5. Display the content of the file.
  cat readme
![ls and cat ss](./screenshots/b02-ls-cat.png)
