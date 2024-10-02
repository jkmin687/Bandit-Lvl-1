# OverTheWire Bandit Level 1

## Objective

The OverTheWire Bandit wargame is a series of challenges designed to teach the basics of Linux command line skills and cybersecurity concepts. Level 1 requires users to find the password to the next level in a file called `-` located in the home directory.

### Skills Learned

- Basic SSH usage 
- Understanding user authentication
- Navigating the command line
- Enhanced knowledge of network protocols and security vulnerabilities.
- Concatenating file names with special characters

### Tools Used

- Linux Terminal
- `ssh`, `ls`, `cat`

## Steps

![Screenshot 2024-10-01 235651](https://github.com/user-attachments/assets/31b6b274-7f40-4214-b02b-fe1c5cf69ade)

The first lesson provided helpful reading material on commands such as cat, ls, and cd, as well as guides to deepen our understanding, including the Advanced Bash Scripting Guide. 

After entering the password from Level 0, I utilized the `ls` command to see which files were in the working directory. Then, I used `cat ./-` to open the file, making sure to use `./` to specify the exact file I wanted to access. With this, I obtained the password to advance to the next level.
