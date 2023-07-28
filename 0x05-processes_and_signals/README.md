## Process and PID 

This readme provides a brief overview of key concepts related to processes and PIDs in computing.

### What is a Process?

A process is a running instance of a program on a computer system. It represents the execution of a specific task or application and contains its own resources, such as memory space and system data.

### What is a PID?

PID stands for Process IDentifier. It is a unique numeric identifier assigned to each running process in a system. PIDs are crucial for managing and interacting with processes.

### How to Find a Process' PID?

To find a process's PID, you can use system-specific commands or tools. For instance, on Unix-based systems, you can use the `ps` command to list running processes along with their PIDs.

### How to Kill a Process?

To terminate or kill a process, you can use the `kill` command on Unix-based systems. It sends a signal to the specified process, requesting it to terminate gracefully.

### What is a Signal?

A signal is a software interrupt delivered to a process, prompting it to take a particular action. Signals can be used to communicate with processes, request termination, or handle various events.

### What are the Two Signals that Cannot be Ignored?

The two signals that cannot be ignored by a process are:

1. SIGKILL (signal number 9): This signal forces a process to terminate immediately without any chance for cleanup or handling.

2. SIGSTOP (signal number 19): This signal suspends a process, pausing its execution until it receives a SIGCONT signal.

Please note that forceful termination with SIGKILL should be used with caution as it may lead to data corruption or other undesirable effects. It is advisable to try graceful termination using SIGTERM (signal number 15) first and reserve SIGKILL as a last resort.
