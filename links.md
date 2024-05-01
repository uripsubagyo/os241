---
permalink: LINKS/
---

## WEEK 01

1. **[10 Linux Terminal Commands for Beginners](https://www.youtube.com/watch?v=CpTfQ-q6MPU)**

	Students are advised to grasp a variety of Linux commands, with a focus on a core set of 10 commands. While Linux offers a total of 50 commands, it's not necessary to commit all of them to memory; rather, a deep understanding of these fundamental 10 commands suffices

2. **[BASIC VI EDITOR COMMANDS](https://www.marquette.edu/mathematical-and-statistical-sciences/basic-vi-editor-commands.php)**

	The VI editor, a renowned and classic text editor for Linux, operates in two modes: Insert mode, where text is entered into the file, and Command mode, where commands are executed to perfor actions on the file.

3. **[Regular Expressions - Linux Tutorial 10](https://www.youtube.com/watch?v=mpyCeSvGh-M)**

	Utilizing common commands employing Regular Expressions include tr, sed, vi, and grep. Below are descriptions of fundamental Regex symbols.

4. **[How to write a bash script](https://www.youtube.com/watch?v=F-gskSl4pwQ)**

	This tutorial demonstrates the process of creating a bash script. Users of Linux and macOS can interact with their operating systems through Bash, a Unix command line interface. Bash script simplify the process of combining commands into a cohesive program. In Bash scripts, commands executed from the terminal operate seamlessly.


## WEEK 02

1. **[Cyber Security Introduction (Cyber Security Part 1)](https://www.youtube.com/watch?v=rcDO8km6R6c)**

	Watching this video enhances my understanding that the essence of Cyber Security lies in averting data loss, avoiding system downtime, thwarting malicious exploitation, and ensuring adherence to laws and regulations. Additionally, the video emphasizes the principle of refraining from causing harm.

2.  **[The Beginner’s Guide To Online Privacy](https://www.freecodecamp.org/news/the-beginners-guide-to-online-privacy-7149b33c4a3e/)**

	This website proves highly beneficial for novices in the realm of online privacy. Upon perusing its contents, I gained insight into the Pyramid of Privacy, which educates us on safeguarding our data from the foundational level to the pinnacle, encompassing aspects such as operating systems, scripts, and cookies. Furthermore, within this section, I acquired knowledge regarding risk assessment and corresponding solutions.

3. **[Employee Security Policy (Cyber Security Part 2)](https://www.youtube.com/watch?v=CivG_2UqKMg)**

	This video enlightens me on aspects of an Employee Security Policy. It discusses Employee Bonding and Buying, highlighting several key insights: valuing relationships over products, discerning employees' intentions, proactively addressing issues before they escalate, empathetically understanding employee challenges and identifying solutions, recognizing that managers are also employees, and establishing a network of influencers to garner support.

# WEEK 03

1.  **[Operating System Concepts: File-System Interface](https://www.os-book.com/OS10/slide-dir/PPTX-dir/ch13.pptx)**


    This slide covers the role of file systems, their interfaces, design considerations, and trade-offs, encompassing access methods, file sharing, file locking, directory structures, and file-system protection.

2. **[How to encrypt and decrypt files with GPG?](https://www.thesecuritybuddy.com/pgp-and-gpg/how-to-encrypt-and-decrypt-files-with-gpg/)**

```bash
 To encrypt a file with GPG:
	gpg --armor --output output.asc --encrypt --recipient <recipient-userid> <file>

To decrypt a file with GPG:
	gpg --output file.txt --decrypt output.asc

To decrypt a file with GPG symmetric key:
	gpg --output file.txt -d output.asc

To encrypt a file with GPG symmetric key:
	gpg --armor --output output.asc symmetric file.txt
```

3. **[File Systems in Operating System: Structure, Attributes, Types](https://www.guru99.com/file-systems-operating-system.html)**

	The concept of a "file" denotes a collection of interconnected data stored on secondary or non-volatile mediums like magnetic disks, optical disks, or tapes. I/O functionality accommodates various storage device types. Upon user logout, the files stored on a disk or similar storage medium persist. For an operating system to identify it, a File Structure must adhere to a predefined format. The operating system's ability to differentiate between different file types, such as text files, binary files, and source files, is known as file typing.

## WEEK04

1. **[Addressing, Shared Lib, & Pointer](https://docos.vlsm.org/Slides/os04.pdf)**

	In this slide, I gain insights into providing a detailed description of various ways of organizing memory hardware, discussing various memory-management techniques. Additionally, it offers an in-depth exploration of the Intel Pentium, which supports both pure segmentation and segmentation with paging. The slide also references Contiguous Memory Allocation, Paging, the Structure of the Page Table, and Swapping.

2. **[Memory Management¶](https://docs.kernel.org/admin-guide/mm/index.html)**

	The Linux memory management subsystem is responsible for supervising the system's memory. This encompasses implementing demand paging and virtual memory, allocating memory for both kernel internal structures and user space programs, mapping files into process address spaces, and various other tasks.

3. **[Memory Adressing in C](https://www.w3schools.com/c/c_memory_address.php#:~:text=When%20a%20variable%20is%20created,stored%20in%20this%20memory%20address.)**

	This link pertains to the addressing system within the C programming language.

4.  **[What are the differences between static and dynamic (shared) library linking?](https://cs-fundamentals.com/tech-interview/c/difference-between-static-and-dynamic-linking)** 

	Linking is the process of combining external programs required by the program we write for its successful execution. Static and dynamic linking are two processes of assembling and merging multiple object files to create a single executable. Here, we will discuss the differences between them.

## WEEK05


1. **[What is Demand Paging in OS (Operating System)?](https://www.javatpoint.com/os-demand-paging)** 

	In computer operating systems, demand paging is a virtual memory management technique employed instead of anticipatory paging. With demand paging, the operating system transfers a disk page into physical memory solely when it's accessed and not already present in memory, indicated by a page fault. 



2. **[What is virtual memory? – Gary explains](https://www.youtube.com/watch?v=2quKyPnUShQ)** 

	Put simply, the analogy between physical memory and virtual memory can be likened to the process of shipping inventory to a warehouse. Memory corresponds to the storage capacity of the warehouse, while virtual memory represents incoming shipments being managed either for storage in their designated location or for immediate use within the facility, whether for further processing or operational functions.

3. **[Virtual Memory in Operating System](https://www.geeksforgeeks.org/virtual-memory-in-operating-system/)** 

	Virtual Memory is a method of managing storage where secondary memory is treated as an extension of the main memory. It enables programs to utilize addresses that are translated into corresponding machine addresses, thereby allowing a clear distinction between memory system addresses for physical storage locations and program addresses for memory references.

### WEEK06

1.  **[Operating System - Processes](https://www.tutorialspoint.com/operating_system/os_processes.htm)** 

	A process essentially refers to a program that is currently running. Its execution follows a sequential order. It is characterized as a unit of work within the system. Once a program is loaded into memory and begins execution, it is segmented into four parts: stack, heap, text, and data. The diagram below illustrates a simplified arrangement of a process within the main memory.

2. **[Threads in Operating System (OS)](https://www.javatpoint.com/threads-in-operating-system)** 

	A thread, also known as a thread of execution or control, represents a singular, uninterrupted flow responsible for executing the tasks within a process. Threads are capable of operating within processes across various operating systems, and multiple threads can exist within a single process. Each thread within the same process maintains its own program counter, startup records, and control blocks. Threads are commonly described as lightweight versions of processes.

3.  **[fork() in C](https://www.geeksforgeeks.org/fork-system-call/)** 


	The fork system call is utilized to generate a new process known as the child process, which operates concurrently with the process invoking the fork() call, known as the parent process. Upon the creation of a new child process, both processes proceed to execute the subsequent instruction following the fork() system call. The child process inherits the same program counter (pc), CPU registers, and open files from the parent process.

### WEEK 07

1.  **[Deadlock Dan Starvation](https://www.gurupendidikan.co.id/deadlock-dan-starvation/)** 

		Deadlock occurs when multiple processes are at a standstill, each waiting for the other to release resources they currently hold, leading to a halt in progress for all involved processes.

2.  **[What is a semaphore? How do they work? (Example in C)](https://www.youtube.com/watch?v=ukM_zzrIeXs)**

		A semaphore is an integer variable utilized as a signal determining whether a process can access the critical section of code or specific resources. There exist two classifications of semaphores: Binary, with values restricted to 0 or 1, and Counting, capable of adopting any integer value.


### WEEK 08

1.  **[How to build Linux From Scratch 11.2 (Chap 1-5)](https://www.youtube.com/playlist?list=PLyc5xVO2uDsDlbR_LTP37nG6g4vbSSxSZ)**

		These video tutorials illustrate the process of replacing the operating system on a Windows 10 PC, or any other version or OS, with your preferred Linux distribution using the Linux From Scratch 11.2 installation method.

2. **Preemptive and Non-Preemptive Scheduling
](https://www.geeksforgeeks.org/preemptive-and-non-preemptive-scheduling/)**


		Preemptive scheduling occurs when a process transitions either from the running state to the ready state or from the waiting state to the ready state. Non-preemptive scheduling, on the other hand, is applied when a process concludes or shifts from the running state to the waiting state.
