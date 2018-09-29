# ch02intro
Introduction to OS, Chapter 02

Read [Introduction to OS](http://pages.cs.wisc.edu/~remzi/OSTEP/intro.pdf) and answer the following review questions.

1. **What is an operating system? What does it do?** There is a body of software, in fact, that is responsible for making it easy to run programs (even allowing you to seemingly run many at the same time), allowing programs to share memory, enabling programs to interact with devices, and other fun stuff like that. That body of software is called the operating system 
2. **What is virtualization?** When  the OS takes a physical resource (such as
the processor, or memory, or a disk) and transforms it into a more gen-
eral, powerful, and easy-to-use virtual form of itself
3. **How does an OS provide access to its features?** through some interfaces(APIs) and standard libraries
4. **What illusion does a virtualized CPU provide?** the illusion that the system has a
very large number of virtual CPUs
    - **How does this affect the user experience?** Turning a single CPU (or small set of
them) into a seemingly infinite number of CPUs and thus allowing many
programs to seemingly run at once
    - **How does this affect the developer experience?** he can ran many programms at once without scheduling
    - **What if the CPU were not virtualized?** will run every programm one by one until each of them will end
5. **What is a memory address?** reference to a specific memory location used at various levels by software and hardware
6. **What is memory virtualization?** decouples volatile random access memory (RAM) resources from individual systems in the data center, and then aggregates those resources into a virtualized memory pool available to any computer in the cluster
    - **Why would we want this?** applications can take advantage of a very large amount of memory to improve overall performance, system utilization, increase memory usage efficiency, and enable new use cases.
8. **What happens if you write a C/C++ program that writes past the end of an array?**  anything, depends on circumstances
      - **Can this affect other programs?** yes, it can
9. **What is a thread?** smallest sequence of programmed instructions that can be managed independently by a scheduler, which is typically a part of the operating system
10. **Why would we ever write a multi-threaded program?** for example, to solve the asynchrony problem
11. **What is atomicity?** guarantee of isolation from interrupts, signals, concurrent processes and threads
    - **Is a C/C++ statement atomic?** yes
    - **Is a Java statement atomic?** yes
    - **Is an assembler statement atomic?** it depends

13. **What does persistence mean?** object and process characteristics that continue to exist even after the process that created it ceases or the machine it is running on is powered off

14. **How does OS hard drive virtualization differ from CPU & memory virtualization?** your answer goes here 
15. **How does running multiple programs at the same time increase CPU efficiency?** your answer goes here 
16. **What is multiprogramming?** Instead of just running one
job at a time, the OS would load a number of jobs into memory and switch
rapidly between them, thus improving CPU utilization
