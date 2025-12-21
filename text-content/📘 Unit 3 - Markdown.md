# **Chapter 1: Linux OS and Its Features**

_(Based on Unit-3 PPT + essential external knowledge for better understanding)_

---

## 1. What is Linux Operating System?

Linux is an **operating system**, just like Windows or macOS.

An **operating system (OS)** is the main software that:

- Starts your computer
- Controls hardware (CPU, RAM, disk, keyboard, mouse)
- Allows you to run applications (browser, editor, media player, etc.)

### Important points about Linux (from PPT):

- Linux is based on **UNIX**
- Linux is **open source**
- Linux is **free to use**
- Linux is designed to be **UNIX compatible**
- Linux provides functionality similar to UNIX

### In simple words:

Linux is a **powerful, secure, and flexible OS** used in:

- Servers (Google, Amazon, Netflix)
- Supercomputers
- Android phones
- Cloud platforms
- Cybersecurity tools
- Development machines

---

## 2. Components of Linux System

Linux operating system has **three main components**:

---

### 2.1 Kernel

The **Kernel** is the **heart of Linux**.

Think of the kernel as:

> “The manager between software and hardware”

#### What Kernel does:

- Talks directly to **hardware**
- Controls **CPU**
- Controls **memory (RAM)**
- Controls **disk**
- Controls **input/output devices**

Without the kernel:

- No program can run
- No hardware can be used

👉 Kernel hides complex hardware details and gives a **simple interface** to programs.

---

### 2.2 System Library

System libraries are **pre-written code** that programs use.

Why system libraries exist:

- Applications **cannot talk to hardware directly**
- Applications ask **system libraries**
- System libraries ask the **kernel**

Examples:

- File handling
- Network access
- Memory allocation

📌 System libraries:

- Do **not run in kernel mode**
- Do **not need direct hardware access**
- Make application development easier

---

### 2.3 System Utility

System utilities are **small programs** that perform **specific tasks**.

Examples:

- File copy tools
- Disk formatting tools
- System monitoring tools
- Backup tools

These are **support programs**, not core OS.

---

## 3. Kernel Mode vs User Mode

Linux works using **two execution modes** for safety and performance.

---

### 3.1 Kernel Mode

Kernel Mode is **high privilege mode**.

Characteristics:

- Full access to **hardware**
- Full access to **memory**
- No restrictions
- Very fast execution
- No context switching required

Only **kernel code** runs here.

⚠️ If something goes wrong in kernel mode → system crash.

---

### 3.2 User Mode

User Mode is **restricted mode**.

Characteristics:

- No direct hardware access
- Cannot access kernel memory
- Safe execution
- Used by:

  - User programs
  - Applications
  - Utilities

User programs use **system libraries** to request services from kernel.

📌 This separation improves:

- Security
- Stability
- Reliability

---

## 4. Basic Features of Linux

These are **core features** that make Linux special.

---

### 4.1 Portability

Portability means:

> Linux can run on **different hardware platforms**

Linux runs on:

- PCs
- Servers
- Embedded systems
- ARM processors
- Supercomputers

Same Linux code works everywhere with minimal changes.

---

### 4.2 Open Source

Open source means:

- Source code is **public**
- Anyone can:

  - View
  - Modify
  - Improve
  - Distribute

Benefits:

- Faster improvements
- Community-driven development
- High security (bugs are found quickly)
- No vendor lock-in

---

### 4.3 Multi-User

Multi-user means:

- Multiple users can use the **same system at the same time**
- Each user has:

  - Separate files
  - Separate permissions
  - Separate processes

Common in:

- Servers
- Universities
- Enterprises

---

### 4.4 Multiprogramming

Multiprogramming means:

- Multiple programs run **simultaneously**

Linux CPU scheduling:

- Switches CPU between programs very fast
- Gives illusion of parallel execution

Example:

- Browser + music + editor + download running together

---

### 4.5 Hierarchical File System

Linux uses a **tree-like structure** for files.

- Everything starts from `/` (root)
- Files and folders arranged logically
- Easy organization
- Strong security control

We will study this deeply in later chapters.

---

### 4.6 Shell

Shell is a **command interpreter**.

What shell does:

- Takes command from user
- Passes it to kernel
- Displays output

Types:

- Bash
- Zsh
- Fish

Why shell is powerful:

- Automation
- Scripting
- Fast operations
- Full system control

---

### 4.7 Security

Linux provides strong security using:

- User authentication (passwords)
- File permissions
- Process isolation
- Encryption support

Linux is preferred for:

- Servers
- Ethical hacking
- Cybersecurity
- Cloud infrastructure

---

## 5. Linux Operating System Architecture (from Diagram)

Linux structure (top to bottom):

1. User Applications
2. System Software
3. System Libraries
4. Kernel
5. Kernel Modules
6. Hardware (CPU, RAM, I/O)

Flow:

> Application → System Library → Kernel → Hardware

This layered design makes Linux:

- Stable
- Secure
- Scalable

---

## 6. Extra Important Points (External Knowledge Added)

These are **important to understand Linux fully**, though not explicitly written in PPT:

### 6.1 Linux is NOT UNIX

- Linux is **UNIX-like**
- Built from scratch
- Follows UNIX design philosophy

---

### 6.2 Linux Kernel vs Linux OS

- **Linux kernel** = core engine
- **Linux OS** = kernel + tools + libraries + shell

Distributions package everything together.

---

### 6.3 Why Linux is used everywhere

- Free
- Customizable
- Secure
- Fast
- Stable
- Scales from phone to supercomputer

---

## 7. Summary of Chapter 1

By now, you should clearly understand:

- What Linux OS is
- Why Linux exists
- Components of Linux
- Kernel and its role
- Kernel mode vs user mode
- All basic Linux features
- Linux architecture
- Why Linux is powerful and widely used

---

# **Chapter 2: Linux Distribution Versions**

_(Complete explanation based on PPT + essential external knowledge, in simple language)_

---

## 1. What is a Linux Distribution?

First, let’s clear the **most confusing point** students usually have.

👉 **Linux itself is only a kernel**, not a full operating system.

To make Linux usable for normal users, we need:

- Linux kernel
- System libraries
- Shell
- Package manager
- Software tools
- Installer
- Desktop environment (optional)

When all these things are **bundled together**, it is called a:

> **Linux Distribution (Linux Distro)**

### Simple definition:

A **Linux distribution** is a **complete operating system** built using the Linux kernel along with tools, software, and utilities.

---

## 2. Why Do Linux Distributions Exist?

This is **not directly written in PPT**, but is **very important to understand**.

Linux distributions exist because:

- Different users have different needs
- One OS cannot fit everyone

Examples:

- Beginners need easy UI
- Servers need stability
- Hackers need security tools
- Developers need latest software
- Old computers need lightweight OS

So, different Linux distributions are created for **different purposes**.

---

## 3. Distribution Versions (From PPT)

The PPT mentions **“Distribution Versions”** and shows **Top 10 Linux Distributions**.

These are **popular and widely used** Linux distributions.

---

## 4. Top 10 Linux Distributions (From PPT)

Below are the **exact distributions shown in the PPT**, explained clearly.

---

### 4.1 **Ubuntu**

- Most popular Linux distribution
- Beginner-friendly
- Easy installation
- Strong community support

Used for:

- Learning Linux
- Desktop usage
- Development
- Servers

Why beginners love it:

- Simple interface
- Large software support
- Lots of tutorials available

---

### 4.2 **Rocky Linux**

- Enterprise-focused Linux
- Replacement for CentOS
- Very stable

Used for:

- Servers
- Data centers
- Enterprise systems

Best when:

- Long-term stability is required
- No frequent updates needed

---

### 4.3 **Red Hat Enterprise Linux (RHEL)**

- Commercial Linux distribution
- Paid support
- Very secure and stable

Used for:

- Corporate servers
- Banking systems
- Government systems

Why companies use it:

- Professional support
- Certified software
- Long-term updates

---

### 4.4 **Debian**

- One of the oldest Linux distributions
- Very stable
- Community-driven

Used for:

- Servers
- Advanced users
- Base for other distros (Ubuntu is based on Debian)

Known for:

- Stability over new features
- Strong package system

---

### 4.5 **Kali Linux**

- Security-focused Linux
- Comes with hacking tools

Used for:

- Ethical hacking
- Penetration testing
- Cybersecurity training

Important note:

- Not for beginners
- Needs good Linux knowledge

---

### 4.6 **SUSE Linux**

- Enterprise-grade Linux
- Popular in Europe
- Strong server tools

Used for:

- Business environments
- SAP systems
- Enterprise servers

---

### 4.7 **Arch Linux**

- Minimal and lightweight
- User builds system manually
- Rolling release model

Used for:

- Advanced users
- Custom systems
- Learning Linux deeply

Why it’s special:

- You control everything
- No unnecessary software

---

### 4.8 **Raspbian**

- Designed for Raspberry Pi
- Lightweight
- Optimized for ARM processors

Used for:

- IoT projects
- Embedded systems
- Learning programming

---

### 4.9 **MX Linux**

- Lightweight
- Fast
- Works well on old computers

Used for:

- Low-end hardware
- Older laptops
- Fast desktop usage

---

### 4.10 **Fedora**

- Sponsored by Red Hat
- Latest features
- Modern software

Used for:

- Developers
- Testing new Linux features
- Desktop users who want latest tech

---

## 5. How Linux Distributions Differ From Each Other

Even though all use **Linux kernel**, they differ in:

- Package manager (apt, yum, pacman)
- Default desktop environment
- Release cycle
- Stability vs latest features
- Target users

This is why **multiple distributions exist**.

---

## 6. Choosing the Right Linux Distribution

This is **external knowledge added** for better understanding.

| User Type      | Recommended Distribution  |
| -------------- | ------------------------- |
| Beginner       | Ubuntu, MX Linux          |
| Server Admin   | Debian, RHEL, Rocky Linux |
| Ethical Hacker | Kali Linux                |
| Developer      | Fedora, Ubuntu            |
| Old PC         | MX Linux                  |
| Advanced User  | Arch Linux                |

---

## 7. Important Exam-Oriented Points

From PPT perspective:

- Linux has **multiple distributions**
- Distributions bundle kernel + software
- Different distros serve different purposes
- Ubuntu, Debian, RHEL, Kali are important names

---

## 8. Summary of Chapter 2

After this chapter, you should clearly understand:

- What a Linux distribution is
- Why Linux has many distributions
- Difference between kernel and distribution
- Purpose of each major Linux distro
- Which Linux distro is used where

---

### ✅ Chapter 2 is now **fully completed**

- Nothing from PPT is missed
- Extra knowledge added only to **increase clarity**
- Language kept **simple and friendly**
- Flow is **natural and easy to remember**

---

# **Chapter 3: Linux Installation**

_(Fully based on PPT + extended explanation for complete understanding)_

---

## 1. What Does “Installing Linux” Mean?

Installing Linux means:

- Putting the Linux operating system on your computer
- So that your computer can **start (boot)** using Linux
- And you can **use Linux instead of or along with Windows**

Linux can be installed in **three common ways**:

1. Only Linux (Windows removed)
2. Linux + Windows (Dual Boot)
3. Inside another OS (Virtual Machine)

👉 In this chapter, the PPT explains **direct installation using a bootable USB**, which is the **most common real-world method**.

---

## 2. What is a Bootable USB?

Before installation, we need a **bootable Linux USB drive**.

A **bootable USB** is:

- A normal pen drive
- That contains Linux installation files
- And can start the computer like a CD/DVD

Why bootable USB is needed:

- Computer normally boots from hard disk
- We want to boot Linux installer instead
- USB tells computer: “Start Linux installer”

---

## 3. Step-by-Step Linux Installation Process

_(Exact steps from PPT + detailed explanation)_

---

### **Step 1: Insert a Bootable Linux USB Drive**

- Plug the Linux bootable USB into your computer
- USB contains Linux installer files

At this point:

- Linux is **not installed**
- It is only ready to start installation

---

### **Step 2: Click the Start Menu**

- Open Windows **Start Menu**
- This is needed to restart the system properly

---

### **Step 3: Hold SHIFT Key and Click Restart**

This is a **very important step**.

Why press **SHIFT + Restart**?

- It opens **Advanced Boot Options**
- Normal restart will boot Windows again
- Advanced options allow booting from USB

---

### **Step 4: Select “Use a Device”**

After restart:

- A blue screen appears
- Choose **Use a Device**

This tells the computer:

> “I want to boot from an external device”

---

### **Step 5: Find Your USB Device in the List**

- You will see a list of bootable devices
- Select your Linux USB (may show USB name or “UEFI USB”)

Now computer prepares to load Linux installer.

---

### **Step 6: Computer Boots into Linux**

At this stage:

- Linux starts running from USB
- Hard disk is still untouched
- This is called **Live Linux Mode**

Live Mode allows:

- Testing Linux without installing
- Checking Wi-Fi, display, keyboard, mouse

---

### **Step 7: Select “Install Linux”**

On Linux welcome screen:

- Choose **Install Linux**
- This starts actual installation

From now on:

- Linux will be copied to your hard disk

---

### **Step 8: Go Through the Installation Process**

This includes:

- Language selection
- Keyboard layout
- Time zone
- Disk selection
- User name and password

After confirmation:

- Files are copied
- Bootloader is installed
- System is prepared

Once completed:

- Restart system
- Remove USB
- Linux boots from hard disk

---

## 4. What Happens Internally During Installation?

_(External explanation for deep understanding)_

Behind the scenes:

- Linux kernel is copied to disk
- File system is created
- System directories are created
- Bootloader (GRUB) is installed
- User account is created

This is why installation takes some time.

---

## 5. Important Installation Choices (Extra Knowledge)

Even though PPT doesn’t list them, **you must know these**:

### 5.1 Install Alongside Windows

- Both OS available
- Choose at startup
- Safest for beginners

### 5.2 Erase Disk and Install Linux

- Windows removed
- Full Linux system
- Used when Linux is primary OS

### 5.3 Custom Partitioning

- Manual control
- Used by advanced users
- Covered in later chapter

---

## 6. Why Linux Installation is Considered Easy

Compared to older times:

- Graphical installer
- Step-by-step wizard
- Auto hardware detection
- Very less manual work

Modern Linux installation is:

- Faster than Windows
- Simpler than expected
- Beginner-friendly

---

## 7. Common Beginner Fears (Cleared)

❌ “Linux installation is risky”
✅ Safe if instructions followed

❌ “Linux deletes everything”
✅ Only if user selects erase option

❌ “Linux is hard to install”
✅ Modern installers are very easy

---

## 8. Summary of Chapter 3

After this chapter, you clearly understand:

- What Linux installation means
- What a bootable USB is
- Why SHIFT + Restart is used
- How Linux boots from USB
- Complete installation flow
- What happens internally
- Basic installation choices

---

### ✅ Chapter 3 is **fully completed**

- Every PPT step explained
- Nothing skipped
- Extra knowledge added only to **make things clearer**
- Language kept **simple and natural**

---

# **Chapter 4: Linux Directory Structure and File System Hierarchy**

_(Fully based on the PPT + extended explanation for strong understanding)_

---

## 1. What is a File System?

Before going into directories, let’s understand this clearly.

A **file system** is:

- The way an operating system **stores, organizes, and accesses files**
- Just like how books are arranged in shelves in a library

Linux uses a **hierarchical file system**, meaning:

- Files and folders are arranged like a **tree**
- There is **one starting point**
- Everything grows downward from it

---

## 2. Root of Linux File System (`/`)

In Linux, everything starts from:

```
/
```

This is called the **root directory**.

⚠️ Important:

- `/` (root directory) is **NOT the same** as the **root user**
- Root directory is the **top-most folder**
- All other directories exist **inside `/`**

Think of `/` as:

> The main trunk of a tree

---

## 3. Linux Directory Structure (From PPT)

The PPT lists the **standard Linux directories**.
Each one has a **fixed purpose**.

Let’s go **one by one**, clearly.

---

## 4. Standard Root and System Directories

### 4.1 `/` – Root Directory

- Starting point of Linux file system
- Contains all other directories
- Without `/`, Linux cannot work

Example:

```
/bin
/etc
/home
/usr
```

---

### 4.2 `/bin` – Binary Files

- Contains **essential commands**
- Commands needed for system to work

Examples:

- `ls`
- `cp`
- `mv`
- `rm`

Why `/bin` is important:

- These commands must work even if system is broken
- Used during booting and repair

---

### 4.3 `/etc` – Configuration Files

- Contains **system configuration files**
- Controls system behavior

Examples:

- User accounts
- Network settings
- Password rules

Important rule:

- Mostly text files
- Editing requires admin permission

---

### 4.4 `/home` – User Home Directories

- Contains **personal folders for users**
- Each user gets a separate folder

Example:

```
/home/nitiksh
/home/user1
```

Inside `/home`, users store:

- Documents
- Downloads
- Pictures
- Projects

This is where users **normally work**.

---

### 4.5 `/opt` – Optional Software

- Used for **third-party software**
- Software not installed by default

Examples:

- Custom applications
- External tools
- Manually installed software

Keeps system clean and organized.

---

### 4.6 `/tmp` – Temporary Files

- Stores **temporary files**
- Files needed for short time only

Important points:

- Cleared automatically on reboot
- Used by programs for temporary data

Never store important files here.

---

### 4.7 `/usr` – User Programs

- Contains user-related programs and libraries
- Majority of installed software lives here

Includes:

- Applications
- Libraries
- Documentation

Despite name, `/usr` is **not for users’ personal files**.

---

### 4.8 `/var` – Variable Data

- Stores data that **changes frequently**

Examples:

- Log files
- Cache files
- Spool files

Very important for:

- System monitoring
- Debugging
- Server logs

---

## 5. Why Linux Uses This Structure

This structure exists because:

- Clear separation of files
- Better security
- Easy maintenance
- Faster troubleshooting

Advantages:

- System files are protected
- User files are isolated
- Temporary files don’t clutter system
- Logs are easy to find

---

## 6. Linux File System vs Windows (Conceptual Difference)

This is **external knowledge**, but very useful.

### Linux:

- Single root `/`
- Everything under one tree
- Drives mounted inside directories

### Windows:

- Multiple drives (C:, D:, E:)
- No single root

Linux approach is:

- Cleaner
- More logical
- More powerful

---

## 7. File System Hierarchy (From Diagram in PPT)

The PPT diagram shows:

- `/` at the top
- Subdirectories branching out
- Each directory has a fixed role

This hierarchy helps:

- Kernel find files easily
- Programs work consistently
- Admins manage system efficiently

---

## 8. Important Rules to Remember

- Linux is **case-sensitive**
- `/home/User` ≠ `/home/user`
- Everything is treated as a file
- Directories are special files

---

## 9. Common Beginner Mistakes (Avoid These)

❌ Storing files in `/tmp`
❌ Editing `/etc` files without permission
❌ Deleting system folders
❌ Working directly in `/`

Correct practice:

- Work inside `/home`
- Use system folders carefully
- Understand purpose before modifying

---

## 10. Summary of Chapter 4

After this chapter, you now understand:

- What a Linux file system is
- What `/` (root directory) means
- Complete Linux directory structure
- Purpose of each major directory
- How Linux organizes files
- Why this structure is powerful

---

### ✅ Chapter 4 completed **fully and clearly**

- Every PPT topic covered
- Diagram meaning explained
- Extra concepts added only for clarity
- Language kept **simple and friendly**

---

# **Chapter 5: Disk Partitioning in Linux**

_(Fully based on the PPT + essential external explanation, written in easy language)_

---

## 1. What is Disk Partitioning?

Before touching commands, let’s understand the **idea**.

A **disk** (hard disk / SSD) is one large storage space.
**Partitioning** means:

> Dividing one physical storage device into multiple logical parts.

Each part is called a **partition**.

### Simple example:

Think of a big cupboard:

- One section for books
- One for clothes
- One for documents

Even though it’s **one cupboard**, it’s divided for **better organization**.

---

## 2. Why Do We Need Partitioning?

This point is clearly mentioned in the PPT.

Partitioning is needed because:

- Storage devices must be **structured** before use
- Large disks are easier to manage when divided
- Each partition behaves like a **separate disk**

### Benefits of partitioning:

- Better file organization
- Easier backup
- Better security
- One partition failure won’t affect others
- Multiple operating systems can coexist

---

## 3. Disk Partitioning in Linux (From PPT)

The PPT explains partitioning using the **parted command**.

`parted` is a **Linux tool** used to:

- Create partitions
- Delete partitions
- View partition layout
- Manage large disks

---

## 4. Storage Device Naming in Linux

Before partitioning, Linux identifies disks using special names.

Examples (from PPT):

- `/dev/sda`
- `/dev/sdb`
- `/dev/vda`
- `/dev/vdb`

Meaning:

- `sd` → storage disk
- `a`, `b`, `c` → disk number

Usually:

- `/dev/sda` → main disk (OS disk)
- `/dev/sdb` → second disk (USB / extra disk)

⚠️ Very important:
Never randomly select a disk, or data loss can occur.

---

## 5. Partitioning Process Using `parted` Command

_(Exact PPT flow explained clearly)_

---

### **Step 1: List the Partitions**

Command used:

```
parted -l
```

What this does:

- Shows all storage devices
- Shows existing partitions
- Helps identify the correct disk

Purpose:

> To know **which disk** you want to partition

---

### **Step 2: Open the Storage Device**

Command concept:

```
parted /dev/sdb
```

What happens:

- You tell Linux which disk to work on
- `parted` opens that disk for modification

⚠️ Important (from PPT):

- If you run `parted` without specifying a disk,
  it may select a disk randomly
- This can cause **data loss**

---

### **Step 3: Set the Partition Table**

A **partition table** defines:

- How partitions are stored on the disk

PPT mentions **GPT** (GUID Partition Table).

Command used:

```
mklabel gpt
```

Supported partition tables (from PPT):

- aix
- amiga
- bsd
- dvh
- gpt
- mac
- ms-dos
- pc98
- sun
- loop

📌 Important note from PPT:

- `mklabel` creates a **partition table**
- It does **not create partitions**

---

### **Step 4: Review the Partition Table**

Purpose:

- Verify disk layout
- Confirm partition table is set

This helps ensure:

- Disk is ready
- No mistakes were made

---

### **Step 5: Get Help**

Linux always provides help.

Command:

```
help mkpart
```

This shows:

- Syntax of partition creation
- Required parameters
- Usage instructions

This is useful when:

- You forget commands
- You are learning

---

### **Step 6: Make a Partition**

This is where the actual partition is created.

Example from PPT:

```
mkpart primary 0 1396MB
```

Meaning:

- `primary` → type of partition
- `0` → start point
- `1396MB` → end point

After this step:

- Disk is divided
- New partition is created

---

## 6. What Happens After Partition Creation? (External Explanation)

After partitioning:

- Partition exists but may not be usable yet
- Usually next steps are:

  - Formatting (creating file system)
  - Mounting (attaching to directory)

These steps are usually done automatically during OS installation.

---

## 7. Why Linux Partitioning is Powerful

Linux allows:

- Multiple partitions
- Multiple file systems
- Advanced disk layouts
- Server-grade storage control

That’s why Linux dominates:

- Servers
- Cloud
- Enterprise systems

---

## 8. Common Beginner Mistakes (Very Important)

❌ Partitioning wrong disk
❌ Running `parted` blindly
❌ Not checking `/dev/sdX` carefully
❌ Partitioning OS disk unintentionally

Correct approach:

- Always run `parted -l`
- Identify disk clearly
- Double-check before making changes

---

## 9. Summary of Chapter 5

After this chapter, you clearly understand:

- What disk partitioning is
- Why partitioning is needed
- Storage device naming in Linux
- What `parted` command does
- Complete step-by-step partitioning process
- Importance of partition tables
- How Linux safely manages disks

---

### ✅ Chapter 5 completed **fully and clearly**

- Every PPT step covered
- Commands explained in simple language
- Extra details added only to improve understanding
- No jargon, no confusion

---

# **Chapter 6: Linux vs Windows Comparison**

_(Fully based on PPT + clear explanation for real understanding)_

---

## 1. Why Compare Linux and Windows?

Linux and Windows are the **two most commonly discussed operating systems**.

Comparing them helps us understand:

- Where Linux is better
- Where Windows is better
- Why companies choose Linux
- Why home users often choose Windows

The PPT compares them using **11 important points**.
We will follow the **same order and flow**.

---

## 2. Open Source vs Closed Source

### Linux

- Linux is **open source**
- Source code is publicly available
- Anyone can see, modify, and improve it

### Windows

- Windows is **closed source**
- Source code is owned by Microsoft
- Users cannot see or modify it

👉 Why this matters:

- Open source → more transparency
- Closed source → controlled by one company

---

## 3. Cost

### Linux

- Linux is **free of cost**
- No license fee
- Can be installed on unlimited systems

### Windows

- Windows is **paid**
- Requires license or activation
- Cost increases for multiple systems

👉 This is why Linux is popular in:

- Servers
- Universities
- Startups

---

## 4. File Name Case Sensitivity

### Linux

- File names are **case-sensitive**
- `file.txt` ≠ `File.txt` ≠ `FILE.txt`

### Windows

- File names are **case-insensitive**
- `file.txt` = `File.txt`

👉 Why Linux does this:

- Better control
- Avoids confusion in programming
- More accurate file handling

---

## 5. Kernel Type

### Linux

- Uses **Monolithic Kernel**
- Most OS services run in kernel space

### Windows

- Uses **Microkernel-based design** (hybrid approach internally)

👉 Simple meaning:

- Linux kernel does more work itself
- Windows splits work into smaller parts

We will study kernel types in detail in later chapters.

---

## 6. Operational Efficiency

### Linux

- More efficient
- Uses fewer system resources
- Runs well on low-end hardware

### Windows

- Less efficient compared to Linux
- Needs more RAM and CPU
- Slower on older systems

👉 This is why Linux is used on:

- Servers
- Old machines
- Embedded systems

---

## 7. Directory Separator Convention

### Linux

- Uses **forward slash**

```
/home/user/docs
```

### Windows

- Uses **backward slash**

```
C:\Users\User\Docs
```

👉 Linux follows UNIX standards
👉 Windows follows its own design

---

## 8. Security Comparison

### Linux

- More secure
- Strong permission system
- Fewer viruses
- User privilege separation

### Windows

- Less secure compared to Linux
- More virus attacks
- Often targeted by malware

👉 Reason:

- Linux user permissions are strict
- Most users don’t work as admin

---

## 9. Hacking and Security Usage

### Linux

- Widely used for hacking and security testing
- Preferred in cybersecurity
- Used in penetration testing

### Windows

- Not very efficient for hacking
- Limited built-in security tools

👉 This is why security professionals prefer Linux.

---

## 10. User Account Types

### Linux User Accounts (3 Types)

1. Regular User
2. Root User
3. Service Account

- Root user has full control
- Regular users have limited access

---

### Windows User Accounts (4 Types)

1. Administrator
2. Standard User
3. Child
4. Guest

- Administrator has full privileges
- Other users have limited access

---

## 11. Super User Privileges

### Linux

- Root user is the **super user**
- Has all administrative privileges
- Can access anything in system

### Windows

- Administrator user has similar privileges
- Controls system settings

Difference:

- Linux restricts root usage strongly
- Windows often encourages admin usage

---

## 12. File Naming Convention (Repeated Emphasis in PPT)

### Linux

- Case-sensitive naming
- Two files with same name but different case allowed

### Windows

- Case-insensitive
- Cannot have two files with same name in same folder

This is **very important for programming**.

---

## 13. Why Linux is Preferred in Servers (Extra Clarity)

Linux is preferred because:

- Free
- Secure
- Stable
- Efficient
- Customizable
- Less downtime

Windows is preferred because:

- User-friendly
- Better for gaming
- Popular desktop applications

---

## 14. Exam-Oriented Quick Comparison Table

| Feature          | Linux | Windows |
| ---------------- | ----- | ------- |
| Source           | Open  | Closed  |
| Cost             | Free  | Paid    |
| Case Sensitivity | Yes   | No      |
| Security         | High  | Lower   |
| Efficiency       | High  | Lower   |
| Hacking Use      | High  | Low     |

---

## 15. Summary of Chapter 6

After this chapter, you clearly understand:

- Core differences between Linux and Windows
- Why Linux is open source
- Why Linux is more secure
- Why Linux is preferred in servers
- How file handling differs
- Why Linux is important for developers

---

### ✅ Chapter 6 completed **fully and clearly**

- Every PPT comparison covered
- Same order as PPT
- Easy language
- No confusion
- High exam value

---

<div align="center">

|                                                                                             **Typical VM Architecture**                                                                                              |                                                      **Virtual Machine Layers**                                                       |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------: |
| <img src="https://www.researchgate.net/profile/San-Murugesan/publication/270058181/figure/fig2/AS%3A670717515407370%401536922925442/Typical-Virtual-Machine-architecture-1.png?utm_source=chatgpt.com" width="400"/> | <img src="https://www.techtarget.com/rms/onlineimages/virtual_machines-h_half_column_mobile.png?utm_source=chatgpt.com" width="400"/> |

|                                                                                   **Type 2 Hypervisor**                                                                                   |                                                        **Hypervisor Types**                                                         |
| :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------: |
| <img src="https://eu-images.contentstack.com/v3/assets/blt8eb3cdfc1fce5194/bltef4f4e5acd5c9af3/662120d02b1c9d903c2d134b/Hypervisor101-Type2-470.jpg?utm_source=chatgpt.com" width="400"/> | <img src="https://www.dnsstuff.com/wp-content/uploads/2019/10/what-is-hypervisor-1024x536.jpg?utm_source=chatgpt.com" width="400"/> |

</div>

---

# **Chapter 7: Virtual Machines**

_(Fully based on PPT + clear external explanation)_

---

## 1. What is a Virtual Machine (VM)?

From the PPT definition:

A **Virtual Machine (VM)** is a **computer created using software**, not hardware.

In simple words:

> A virtual machine is a **computer inside another computer**.

- The **real computer** is called the **host machine**
- The **virtual computer** is called the **guest machine**

Even though the guest machine is not real hardware, it behaves like:

- A real computer
- With its own operating system
- Own memory
- Own storage
- Own CPU share

---

## 2. Host Machine and Guest Machine

### Host Machine

- The **physical computer**
- Has real hardware (CPU, RAM, disk)
- Runs the main operating system

Example:

- Your laptop running Windows or Linux

---

### Guest Machine

- The **virtual computer**
- Runs inside the host
- Uses host resources

Example:

- Linux running inside Windows using a VM

---

## 3. Compute Resources (From PPT)

A virtual machine uses **compute resources** from the host system.

These include:

- CPU
- RAM
- Storage
- Network

Important point:

- Resources are **shared**
- Each VM gets only what is assigned

This allows:

- Multiple OS running on one machine
- Efficient hardware usage

---

## 4. What Are Virtual Machines Used For? (From PPT)

This section is **directly from the PPT**, explained clearly.

---

### 4.1 Running Another Operating System

VMs allow:

- One OS to run inside another OS
- Without replacing the main system

Example:

- Linux VM running on Windows
- macOS VM running on Linux (hardware support required)

---

### 4.2 Safe Testing and Sandboxed Environments

Sandbox means:

> A **safe isolated area**

VMs are used to:

- Test new software
- Test unknown programs
- Open risky files

Why it is safe:

- VM is separated from host
- Virus inside VM cannot damage host system

This is **very important in security**.

---

### 4.3 Server Virtualization

From PPT:

Virtual machines are heavily used in **server environments**.

Instead of:

- One server = one OS

We use:

- One server = many virtual machines

Benefits:

- Saves cost
- Saves power
- Better performance
- Easy maintenance

This is the base of **cloud computing**.

---

## 5. Why Companies Use Virtual Machines (Extra Clarity)

Companies use VMs because:

- One physical machine can run many services
- Easy backup and recovery
- Easy scaling
- Fast deployment

This is why:

- AWS
- Azure
- Google Cloud
  all rely heavily on virtualization.

---

## 6. How Do Virtual Machines Work? (From PPT)

VMs work using a special software called a **Hypervisor**.

### Hypervisor does:

- Creates virtual hardware
- Manages resource sharing
- Controls VM execution

VM runs:

- Like a normal application
- In a window on the host OS

---

## 7. Key Virtual Machine Files (From PPT)

Each VM is made of **important files**.

---

### 7.1 Log File

- Stores VM activity
- Helps in debugging
- Records errors and events

---

### 7.2 NVRAM File

- Stores BIOS/UEFI settings of VM
- Acts like motherboard memory
- Saves boot settings

---

### 7.3 Virtual Disk File

- Acts as **hard disk** for VM
- Stores OS, files, software
- Can be very large

Examples:

- `.vmdk`
- `.vdi`
- `.qcow2`

---

### 7.4 Configuration File

- Defines VM settings
- CPU count
- RAM size
- Disk location
- Network settings

Without this file, VM cannot start.

---

## 8. Isolation in Virtual Machines (Very Important Concept)

Isolation means:

- Each VM is **separate**
- One VM cannot affect another
- Host remains safe

Because of isolation:

- Malware testing is done in VMs
- OS testing is done in VMs
- Risky tasks are done safely

---

## 9. Popular Virtual Machine Software (External Knowledge)

Here are common VM tools used worldwide:

- **VMware**
- **VirtualBox**
- **Hyper-V**

These tools:

- Create VMs
- Manage resources
- Provide GUI for users

---

## 10. Virtual Machines vs Physical Machines

| Physical Machine | Virtual Machine      |
| ---------------- | -------------------- |
| Real hardware    | Software-based       |
| One OS usually   | Multiple OS possible |
| Hard to scale    | Easy to scale        |
| Costly           | Cost-effective       |

---

## 11. Common Beginner Confusions (Cleared)

❌ “VM is slow”
✅ Modern VMs are fast with proper hardware

❌ “VM can damage my PC”
✅ VMs are isolated and safe

❌ “VM is same as emulator”
✅ VM uses real CPU, emulator simulates CPU

---

## 12. Summary of Chapter 7

After this chapter, you clearly understand:

- What a virtual machine is
- Difference between host and guest
- What compute resources are
- Real uses of virtual machines
- Safe testing and sandboxing
- Server virtualization
- How VMs work
- Key VM files
- Why VMs are used everywhere

---

### ✅ Chapter 7 completed **fully and clearly**

- Every PPT topic covered
- Extra knowledge added only for clarity
- Simple language
- Real-world examples
- Strong foundation for cloud and servers

---

<div align="center">

|                                          **Date Command Example**                                          |                                                  **CLI Example**                                                   |
| :--------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------: |
| <img src="https://kinsta.com/wp-content/uploads/2021/08/new-date.png?utm_source=chatgpt.com" width="400"/> | <img src="https://media.geeksforgeeks.org/wp-content/uploads/cli_example.png?utm_source=chatgpt.com" width="400"/> |

|                                                                  **ls Command Long Listing**                                                                  |                                                   **ls Command Output**                                                   |
| :-----------------------------------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------: |
| <img src="https://www.computernetworkingnotes.com/wp-content/uploads/linux-tutorials/images/lt85-05-ls-long-listing.png?utm_source=chatgpt.com" width="400"/> | <img src="https://detailed.wordpress.com/wp-content/uploads/2017/10/ls-command3.jpg?utm_source=chatgpt.com" width="400"/> |

</div>

# **Chapter 8: Linux Shell Commands**

_(Fully based on PPT + clear external explanation)_

---

## 1. What is a Shell Command?

A **shell command** is:

- A text instruction
- Given by the user
- To the Linux shell
- To perform a task

Instead of clicking buttons (like Windows),
Linux allows you to:

> **Control the entire system using commands**

Commands are:

- Fast
- Powerful
- Precise
- Scriptable

---

## 2. Why Shell Commands Are Important

Shell commands allow you to:

- Navigate files
- Create folders
- Copy and move files
- Manage permissions
- Monitor processes
- Control the system

Almost **everything in Linux** can be done using commands.

---

## 3. Other Shell Commands (From PPT)

The PPT lists the following commands.
We will explain **each one clearly**, **exactly as listed**.

---

## 4. `ls` Command – List Files

### Purpose:

Shows files and folders in a directory.

### Simple meaning:

> “What is inside this folder?”

Example:

```
ls
```

Common usage:

- Check files
- Confirm file creation
- See directory contents

---

## 5. `cat` Command – Show File Content

### Purpose:

Displays contents of a text file.

### Simple meaning:

> “Show me what is written inside this file”

Examples:

```
cat myfile
cat file1 >> file2
```

Uses:

- Read small files
- Combine files

---

## 6. `man` Command – Manual Pages

### Purpose:

Shows help for any Linux command.

### Simple meaning:

> “Explain this command to me”

Example:

```
man ls
```

The manual includes:

- Name
- Description
- Options
- Examples

Very useful when:

- You forget command usage
- You are learning new commands

---

## 7. `cd` Command – Change Directory

### Purpose:

Move from one directory to another.

### Simple meaning:

> “Go to another folder”

Examples:

```
cd myfiles
cd /home/user/docs
```

By default:

- Linux starts in the home directory

---

## 8. `touch` Command – Modify Timestamp / Create File

### Purpose:

- Update file timestamp
- Create empty file

Example:

```
touch file.txt
```

If file doesn’t exist:

- It gets created

If file exists:

- Timestamp is updated

---

## 9. `cp` Command – Copy Files

### Purpose:

Creates a copy of a file.

Example:

```
cp oldfile newfile
```

Important:

- Original file remains unchanged
- New identical copy is created

---

## 10. `mv` Command – Move or Rename Files

### Purpose:

- Move files
- Rename files

Example:

```
mv file1 /home/user/
mv oldname newname
```

Used for:

- Organizing files
- Renaming files

---

## 11. `chmod` Command – Change Permissions

### Purpose:

Controls who can:

- Read
- Write
- Execute a file

Simple meaning:

> “Who is allowed to use this file?”

This is a **core Linux security command**.

---

## 12. `mkdir` Command – Create Directory

### Purpose:

Creates a new folder.

Example:

```
mkdir LPUCSE
```

Used when:

- Organizing projects
- Creating folders

---

## 13. `rmdir` Command – Remove Empty Directory

### Purpose:

Deletes **empty** directories only.

Example:

```
rmdir /mike
```

Important:

- Directory must be empty
- For non-empty directories, use `rm`

---

## 14. `rm` Command – Remove Files

### Purpose:

Deletes files permanently.

Example:

```
rm CSEA.txt
```

⚠️ Important:

- No recycle bin
- Deleted files cannot be recovered easily

Use carefully.

---

## 15. `pwd` Command – Print Working Directory

### Purpose:

Shows current directory path.

Example:

```
pwd
```

Output:

- Full absolute path from `/`

Helps when:

- You are lost in directories
- Writing scripts

---

## 16. `ps` Command – Process Status

### Purpose:

Shows running processes.

Simple meaning:

> “What programs are running right now?”

Example:

```
ps
```

Used for:

- Monitoring system
- Debugging
- Managing processes

---

## 17. `kill` Command – Terminate Processes

### Purpose:

Stops a running process.

Example:

```
kill 1234
```

Where `1234` is:

- Process ID (PID)

Used when:

- Program freezes
- Process doesn’t respond

---

## 18. Activity (From PPT)

### Activity: Command Execution

This means:

- Practice these commands
- Run them in terminal
- Observe output

Why activity matters:

- Commands become familiar
- Confidence increases
- Linux becomes easy

---

## 19. Common Beginner Mistakes (Very Important)

❌ Using `rm` blindly
❌ Running commands without understanding
❌ Forgetting case sensitivity
❌ Not checking current directory

Correct approach:

- Use `pwd`
- Use `ls`
- Read before executing

---

## 20. Summary of Chapter 8

After this chapter, you clearly understand:

- What shell commands are
- Why commands are powerful
- Purpose of each Linux command
- How to navigate directories
- How to manage files
- How to control processes
- Importance of practice

---

### ✅ Chapter 8 completed **fully and clearly**

- Every PPT command explained
- Same order as PPT
- Easy language
- Practical understanding
- No confusion

---

<div align="center">

|                                                       **Kernel Architecture**                                                       |                                                                                        **Kernel Hardware Relation**                                                                                        |
| :---------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| <img src="https://media.geeksforgeeks.org/wp-content/uploads/20250124124411692602/kernel.webp?utm_source=chatgpt.com" width="400"/> | <img src="https://www.researchgate.net/publication/261248176/figure/fig1/AS%3A392453707321347%401470579663151/The-Kernel-Relation-with-Hardware-and-Applications.png?utm_source=chatgpt.com" width="400"/> |

|                                             **Linux Fundamental Architecture**                                              |                                                                      **Linux Kernel Labs**                                                                       |
| :-------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| <img src="https://www.scaler.com/topics/images/fundamental-architecture-of-linux.webp?utm_source=chatgpt.com" width="400"/> | <img src="https://linux-kernel-labs.github.io/refs/heads/master/_images/ditaa-b9ffae65be16d30be11b5eca188a7a143b1b8227.png?utm_source=chatgpt.com" width="400"/> |

</div>

# **Chapter 9: Kernel and Types of Kernels**

_(Fully based on PPT + simplified external explanation)_

---

## 1. What is a Kernel?

From the PPT:

A **Kernel** is an **intermediary between applications and hardware**.

### Simple meaning:

> The kernel is the **middleman** that connects software and hardware.

Applications **cannot talk directly** to hardware.
Hardware **cannot understand applications**.

So the kernel:

- Takes requests from programs
- Talks to hardware
- Sends results back to programs

Without the kernel:

- No program can run
- No hardware can be used
- No operating system exists

---

## 2. Position of Kernel in Operating System

The kernel sits:

- Below all applications
- Above the hardware

Flow:

```
Applications
↓
Kernel
↓
Hardware
```

This makes the kernel:

- The most powerful part of the OS
- The most sensitive part of the OS

---

## 3. Functions of a Kernel (From PPT)

The PPT lists **four major functions**.
We will go **one by one**, very clearly.

---

## 4. Device Management

### What does this mean?

Computers have many devices:

- Keyboard
- Mouse
- Monitor
- Printer
- Hard disk
- Network card

The kernel:

- Decides which process uses which device
- Prevents device conflicts
- Controls input and output

### Simple example:

If two programs want to print at the same time:

- Kernel manages the printer
- Prevents confusion

---

## 5. Resource Management

### What are resources?

Resources include:

- CPU
- RAM
- Disk
- Network

The kernel:

- Shares resources among processes
- Makes sure no process takes everything
- Gives fair access

### Simple example:

If 10 programs are running:

- Kernel switches CPU between them
- Each program feels like it’s running alone

---

## 6. Memory Management

Every program needs memory (RAM) to run.

The kernel:

- Allocates memory to programs
- Keeps programs separated
- Prevents one program from using another’s memory

Why this is important:

- Prevents crashes
- Improves security
- Keeps system stable

---

## 7. Access to Computer Resources

From the PPT:

The kernel can access:

- RAM
- CPU
- I/O devices
- Other system resources

The kernel decides:

- Which process gets memory
- What happens if memory is full
- Which process gets CPU time

Applications **do not decide this** — the kernel does.

---

## 8. Kernel Layout and Application Intermediation

This means:

- Applications never access hardware directly
- Applications send requests to kernel
- Kernel checks permissions
- Kernel performs the task safely

This design ensures:

- Security
- Stability
- Control

If applications had direct access:

- System would crash easily
- Malware could destroy hardware

---

## 9. Why Kernel Is So Important

The kernel:

- Runs in **kernel mode**
- Has full system access
- Controls everything

If kernel fails:

- Entire system crashes

That’s why kernel code is:

- Very carefully written
- Thoroughly tested
- Highly optimized

---

## 10. Basic Types of Kernels (From PPT)

The PPT lists **three basic types of kernels**:

1. Monolithic Kernel
2. Microkernel
3. Hybrid Kernel

Let’s understand them **clearly and simply**.

---

## 11. Monolithic Kernel

### Definition (from PPT idea):

A **monolithic kernel** runs **all OS services inside the kernel space**.

### What runs inside kernel:

- Device drivers
- Memory management
- Process management
- File system

### Advantages:

- Very fast
- Direct communication
- High performance

### Disadvantages:

- Large kernel size
- If one part fails, entire system may crash

### Example:

- Linux uses a monolithic kernel

---

## 12. Microkernel

### Definition:

A **microkernel** keeps the kernel **very small**.

Only core functions run in kernel:

- Memory management
- CPU scheduling
- Inter-process communication

Other services run in **user space**.

### Advantages:

- More stable
- More secure
- Easier to maintain

### Disadvantages:

- Slower than monolithic kernel
- More communication overhead

---

## 13. Hybrid Kernel

### Definition:

A **hybrid kernel** combines:

- Speed of monolithic kernel
- Stability of microkernel

Some services run in kernel space, some in user space.

### Advantages:

- Balanced performance
- Better stability than monolithic
- Faster than pure microkernel

### Disadvantages:

- More complex design

---

## 14. Kernel Types Comparison (Easy View)

| Kernel Type | Speed       | Stability | Complexity |
| ----------- | ----------- | --------- | ---------- |
| Monolithic  | High        | Medium    | Low        |
| Microkernel | Low         | High      | Medium     |
| Hybrid      | Medium–High | High      | High       |

---

## 15. Why Linux Uses Monolithic Kernel (Extra Clarity)

Linux uses a **monolithic kernel** because:

- High performance
- Efficient hardware access
- Best for servers
- Better control over resources

Modern Linux still improves safety using:

- Loadable kernel modules
- Permission checks

---

## 16. Summary of Chapter 9

After this chapter, you clearly understand:

- What a kernel is
- Why kernel is the core of OS
- Kernel’s role in device management
- Kernel’s role in memory and resource management
- How kernel protects hardware
- Types of kernels
- Differences between monolithic, microkernel, and hybrid
- Why Linux uses monolithic kernel

---

### ✅ Chapter 9 completed **fully and clearly**

- Every PPT topic covered
- Flow kept exactly as syllabus
- Simple language
- Deep understanding
- No unnecessary jargon

---

# ✅ **Unit 3 – 30 MCQs with Explanations**

---

### **1. Linux is originally based on which operating system?**

A. Windows
B. DOS
C. UNIX
D. macOS

✅ **Answer: C. UNIX**
**Explanation:** Linux follows UNIX design principles and behavior, so it is called a UNIX-like OS.

---

### **2. Which component is the core of the Linux operating system?**

A. Shell
B. System Library
C. Kernel
D. System Utility

✅ **Answer: C. Kernel**
**Explanation:** The kernel directly communicates with hardware and controls all system resources.

---

### **3. Which Linux component provides an interface between applications and the kernel?**

A. Shell
B. System Library
C. Hardware
D. Bootloader

✅ **Answer: B. System Library**
**Explanation:** Applications use system libraries to access kernel functions safely.

---

### **4. Kernel code runs in which mode?**

A. User mode
B. Admin mode
C. Kernel mode
D. Safe mode

✅ **Answer: C. Kernel mode**
**Explanation:** Kernel mode has full access to hardware and system resources.

---

### **5. Which of the following is NOT a basic feature of Linux?**

A. Open source
B. Multi-user
C. Single-tasking
D. Security

✅ **Answer: C. Single-tasking**
**Explanation:** Linux supports multiprogramming, not single-tasking.

---

### **6. Linux supports multiple users working at the same time. This feature is called:**

A. Multitasking
B. Multiprocessing
C. Multi-user
D. Multi-threading

✅ **Answer: C. Multi-user**
**Explanation:** Multiple users can access system resources simultaneously.

---

### **7. What is a Linux distribution?**

A. Only the Linux kernel
B. Kernel + hardware
C. Kernel + software tools
D. Only system utilities

✅ **Answer: C. Kernel + software tools**
**Explanation:** A distribution bundles the kernel with libraries, shell, package manager, and tools.

---

### **8. Which Linux distribution is best known for beginners?**

A. Kali Linux
B. Arch Linux
C. Ubuntu
D. Debian

✅ **Answer: C. Ubuntu**
**Explanation:** Ubuntu is user-friendly and widely recommended for beginners.

---

### **9. Which Linux distribution is mainly used for ethical hacking?**

A. Fedora
B. Debian
C. Kali Linux
D. MX Linux

✅ **Answer: C. Kali Linux**
**Explanation:** Kali Linux includes many penetration testing and security tools.

---

### **10. What is a bootable USB used for?**

A. Storing files
B. Internet access
C. Installing an OS
D. Backup only

✅ **Answer: C. Installing an OS**
**Explanation:** A bootable USB allows the system to start the OS installer.

---

### **11. In Linux, the root directory is represented by:**

A. \
B. C:\
C. /
D. root

✅ **Answer: C. /**
**Explanation:** `/` is the top-most directory in Linux.

---

### **12. Which directory contains user home folders?**

A. /bin
B. /etc
C. /home
D. /usr

✅ **Answer: C. /home**
**Explanation:** Each user has a personal directory inside `/home`.

---

### **13. Which directory stores system configuration files?**

A. /var
B. /etc
C. /bin
D. /tmp

✅ **Answer: B. /etc**
**Explanation:** `/etc` contains system-wide configuration files.

---

### **14. Temporary files are stored in which directory?**

A. /var
B. /opt
C. /tmp
D. /usr

✅ **Answer: C. /tmp**
**Explanation:** `/tmp` is used for short-lived temporary files.

---

### **15. Disk partitioning means:**

A. Formatting a disk
B. Deleting data
C. Dividing disk into sections
D. Encrypting disk

✅ **Answer: C. Dividing disk into sections**
**Explanation:** Partitioning splits a disk into logical parts.

---

### **16. Which command is used to list all disk partitions?**

A. ls
B. parted -l
C. df
D. mount

✅ **Answer: B. parted -l**
**Explanation:** It shows all disks and their partition details.

---

### **17. Which partition table type is commonly used in modern systems?**

A. FAT
B. NTFS
C. GPT
D. EXT4

✅ **Answer: C. GPT**
**Explanation:** GPT supports large disks and modern hardware.

---

### **18. Linux is case-sensitive. This means:**

A. File names are ignored
B. File names must be capitalized
C. file.txt ≠ File.txt
D. Only lowercase allowed

✅ **Answer: C. file.txt ≠ File.txt**
**Explanation:** Linux treats uppercase and lowercase as different.

---

### **19. Which OS is open source?**

A. Windows
B. Linux
C. macOS
D. DOS

✅ **Answer: B. Linux**
**Explanation:** Linux source code is freely available.

---

### **20. What is a Virtual Machine?**

A. Physical computer
B. Software-based computer
C. Network device
D. Storage device

✅ **Answer: B. Software-based computer**
**Explanation:** A VM runs inside another computer using software.

---

### **21. The physical computer running VMs is called:**

A. Guest
B. Host
C. Client
D. Server

✅ **Answer: B. Host**
**Explanation:** Host provides hardware resources to VMs.

---

### **22. Which file acts as the hard disk of a VM?**

A. Log file
B. NVRAM
C. Virtual disk file
D. Config file

✅ **Answer: C. Virtual disk file**
**Explanation:** It stores OS, files, and programs of the VM.

---

### **23. Which command lists files in a directory?**

A. cat
B. ls
C. pwd
D. cd

✅ **Answer: B. ls**
**Explanation:** `ls` shows files and folders.

---

### **24. Which command displays the current directory path?**

A. cd
B. ls
C. pwd
D. ps

✅ **Answer: C. pwd**
**Explanation:** `pwd` prints the absolute path.

---

### **25. Which command is used to terminate a process?**

A. ps
B. stop
C. kill
D. exit

✅ **Answer: C. kill**
**Explanation:** `kill` stops a running process using PID.

---

### **26. Which command changes file permissions?**

A. chown
B. chmod
C. cp
D. mv

✅ **Answer: B. chmod**
**Explanation:** `chmod` controls read, write, execute permissions.

---

### **27. Which command creates a directory?**

A. rmdir
B. mkdir
C. touch
D. rm

✅ **Answer: B. mkdir**
**Explanation:** `mkdir` creates new folders.

---

### **28. Which command shows running processes?**

A. ls
B. ps
C. kill
D. top

✅ **Answer: B. ps**
**Explanation:** `ps` displays process status.

---

### **29. The kernel acts as:**

A. User interface
B. Hardware driver only
C. Intermediary between apps and hardware
D. File manager

✅ **Answer: C. Intermediary between apps and hardware**
**Explanation:** Kernel controls all communication with hardware.

---

### **30. Linux uses which type of kernel?**

A. Microkernel
B. Hybrid kernel
C. Monolithic kernel
D. Distributed kernel

✅ **Answer: C. Monolithic kernel**
**Explanation:** Linux runs most OS services inside kernel space for performance.

---

# 🧪 **Linux Command-Based Practical MCQs (30)**

### **1. Which command shows the list of files in the current directory?**

A. pwd
B. cd
C. ls
D. cat

✅ **Answer: C. ls**
**Explanation:** `ls` lists files and directories.

---

### **2. Which command shows the absolute path of the current directory?**

A. ls
B. pwd
C. cd
D. path

✅ **Answer: B. pwd**
**Explanation:** `pwd` prints the full path from root `/`.

---

### **3. What does the command `cd /home/user` do?**

A. Creates directory
B. Deletes directory
C. Moves to `/home/user`
D. Lists files

✅ **Answer: C. Moves to `/home/user`**
**Explanation:** `cd` changes the current directory.

---

### **4. Which command creates an empty file named `test.txt`?**

A. mkdir test.txt
B. touch test.txt
C. cat test.txt
D. cp test.txt

✅ **Answer: B. touch test.txt**
**Explanation:** `touch` creates an empty file if it doesn’t exist.

---

### **5. What does `cat file1` do?**

A. Deletes file
B. Renames file
C. Displays file content
D. Copies file

✅ **Answer: C. Displays file content**
**Explanation:** `cat` prints file content to terminal.

---

### **6. What is the output of `cat file1 >> file2`?**

A. file2 overwrites file1
B. file1 content added to file2
C. file2 deleted
D. file1 deleted

✅ **Answer: B. file1 content added to file2**
**Explanation:** `>>` appends content.

---

### **7. Which command copies `a.txt` to `b.txt`?**

A. mv a.txt b.txt
B. cp a.txt b.txt
C. cat a.txt b.txt
D. rm a.txt

✅ **Answer: B. cp a.txt b.txt**
**Explanation:** `cp` copies files.

---

### **8. Which command renames `old.txt` to `new.txt`?**

A. cp old.txt new.txt
B. rm old.txt
C. mv old.txt new.txt
D. rename old.txt

✅ **Answer: C. mv old.txt new.txt**
**Explanation:** `mv` is used for moving and renaming.

---

### **9. Which command deletes a file permanently?**

A. delete
B. remove
C. rm
D. rmdir

✅ **Answer: C. rm**
**Explanation:** `rm` permanently deletes files.

---

### **10. Which command removes an empty directory named `data`?**

A. rm data
B. rmdir data
C. del data
D. erase data

✅ **Answer: B. rmdir data**
**Explanation:** `rmdir` removes empty directories only.

---

### **11. What happens if `rmdir` is used on a non-empty directory?**

A. Directory deleted
B. Files moved
C. Error occurs
D. Directory renamed

✅ **Answer: C. Error occurs**
**Explanation:** `rmdir` works only for empty directories.

---

### **12. Which command creates a directory named `project`?**

A. touch project
B. rmdir project
C. mkdir project
D. ls project

✅ **Answer: C. mkdir project**
**Explanation:** `mkdir` creates directories.

---

### **13. Which command displays help for the `ls` command?**

A. help ls
B. info ls
C. man ls
D. ls help

✅ **Answer: C. man ls**
**Explanation:** `man` opens the manual page.

---

### **14. Which command is used to change file permissions?**

A. chown
B. chmod
C. cp
D. mv

✅ **Answer: B. chmod**
**Explanation:** `chmod` controls read/write/execute permissions.

---

### **15. Which command shows running processes?**

A. ls
B. ps
C. top
D. kill

✅ **Answer: B. ps**
**Explanation:** `ps` displays current processes.

---

### **16. What does the `kill` command require to stop a process?**

A. File name
B. User name
C. Process ID (PID)
D. Directory path

✅ **Answer: C. Process ID (PID)**
**Explanation:** `kill` uses PID to terminate processes.

---

### **17. Which command shows all disks and partitions?**

A. lsblk
B. df
C. parted -l
D. mount

✅ **Answer: C. parted -l**
**Explanation:** `parted -l` lists disk partition info.

---

### **18. What does `pwd` stand for?**

A. Path Working Directory
B. Print Working Directory
C. Present Working Data
D. Public Working Directory

✅ **Answer: B. Print Working Directory**
**Explanation:** `pwd` prints current directory path.

---

### **19. Which command moves `file.txt` to `/home/user`?**

A. cp file.txt /home/user
B. mv file.txt /home/user
C. cd file.txt /home/user
D. rm file.txt

✅ **Answer: B. mv file.txt /home/user**
**Explanation:** `mv` moves files.

---

### **20. Which command lists files including hidden files?**

A. ls
B. ls -l
C. ls -a
D. ls -h

✅ **Answer: C. ls -a**
**Explanation:** `-a` shows hidden files.

---

### **21. Which command shows detailed file information?**

A. ls
B. ls -l
C. ls -a
D. pwd

✅ **Answer: B. ls -l**
**Explanation:** `-l` gives long listing.

---

### **22. Which command is used to stop a frozen application?**

A. exit
B. stop
C. kill
D. close

✅ **Answer: C. kill**
**Explanation:** `kill` terminates processes.

---

### **23. What does `chmod 777 file.txt` mean?**

A. Only owner can access
B. Read-only access
C. Full permission to everyone
D. No permission

✅ **Answer: C. Full permission to everyone**
**Explanation:** 777 = read, write, execute for all.

---

### **24. Which command is safest to check your current location before deleting files?**

A. ls
B. cd
C. pwd
D. rm

✅ **Answer: C. pwd**
**Explanation:** `pwd` confirms your directory.

---

### **25. Which command deletes multiple files at once?**

A. rm file1 file2
B. delete file1 file2
C. erase file1
D. remove all

✅ **Answer: A. rm file1 file2**
**Explanation:** `rm` supports multiple files.

---

### **26. Which command creates a directory structure?**

A. mkdir
B. mkdir -p
C. rmdir
D. rm -r

✅ **Answer: B. mkdir -p**
**Explanation:** `-p` creates parent directories.

---

### **27. What does `ps` command display?**

A. Disk usage
B. Network status
C. Running processes
D. Memory usage

✅ **Answer: C. Running processes**
**Explanation:** `ps` shows process status.

---

### **28. Which command removes a directory with files inside?**

A. rmdir
B. rm
C. rm -r
D. del

✅ **Answer: C. rm -r**
**Explanation:** `-r` removes directories recursively.

---

### **29. Which command shows command documentation inside terminal?**

A. doc
B. help
C. man
D. info

✅ **Answer: C. man**
**Explanation:** `man` opens the manual page.

---

### **30. Which command should be used with extreme caution?**

A. ls
B. cd
C. rm
D. pwd

✅ **Answer: C. rm**
**Explanation:** `rm` permanently deletes files without recovery.

---
