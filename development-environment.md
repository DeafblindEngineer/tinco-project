### Development Environment

This is my development environment for low-level system programming and hardware driver development. My distribution is Ubuntu 22.04 LTS (Jammy Jellyfish) with the Gnome Desktop. It has been setup for the following programming languages: Assembly, C, C++

### IDE

I am using Unix as my "IDE" with the following tools:

* **Termail Emulator:** Gnome Terminal
* **Unix Shell:** BASH
* **Text Editor:** Vim
* **Terminal Multiplexer:** Tmux	
* **Machine Emulator:** QEMU

### Dotfiles

```
$ vim ~/.bashrc
$ vim ~/.vimrc
$ vim ~/.tmux.conf
```

**NOTE:** my dotfiles can be found here.

### Installation

```
$ sudo apt install vim		// install the text editor
$ sudo apt install tmux		// install the terminal multiplexer
$ sudo apt install qemu		// install the machine emulator
```

```
$ sudo apt install nasm		// install the Netwide Assembler for the Assembly Language
$ nasm --version
```

```
$ sudo apt install build-essential manpages-dev		// installs the following packages: dpkg-dev, make, libc6-dev, gcc/g++ together with the man pages for the C and C++ Languages
$ whereis gcc
$ which gcc
$ gcc --version
```

```
$ sudo apt install gdb		// install the debugger. It supports: Assembly, C, C++
$ gdb --version
```

```
$ sudo apt install git		// install the distributed version control system
$ git --version
```
