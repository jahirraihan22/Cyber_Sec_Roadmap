<!-- @format -->

# Day 03 Linux 101

Linux is a very popular operating system, like macOS or Windows founded By **Linus Torvald** a Finnish software engineer. It is always favorite for an IT person. Behind this popularity the main features of Linux are:

- It is Open Source.
- It is free. You can always download source code and modify according to your needs
- Vast community.
- Difference of flavor.
- Minimal features based on various needs.
- Most of the cloud computing run on Linux based system.

<p align="center">
 <img src="./resources/linux-cloud.jpg?raw=true" alt="cloud is linux" width="50%" height="50%" />
</p>

> Microsoft has an official Windows Subsystem for Linux [(WSL)](https://learn.microsoft.com/en-us/windows/wsl/about) which you can (and should!) install on Windows. This will give you the ability to run Linux in a very easy way on your windows PC.

### Shell

A shell is a command interpreter that exposes to the user an interface to work with the underlying Linux operating system. It allows you to execute operations using text and commands, and it provides
users advanced features like being able to create scripts. Shells let you performs things ina more optimized way than GUI.There are many types of Shells:

- Bash
- Csh
- Zsh
- Fish

##### [See Linux filesystem](../Terminology/LinuxFilesystem.md)

## Most used Linux commands

- **man** : man command use to get manual of a command. If you want to learn about a command just type man <command> to get manual.

        # syntax man <command>
        man ls

- **ls** : ls is One of the most used command. It is used to show the list of element in directory.

        # ls <option> <directory>
        ls /bin

- **cd** : cd is used to change directory

         # cd <directory>
         cd /bin
         # to go home directory
         cd ~
         # to go one step back from current directory
         cd ..
