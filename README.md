# OS




What is an Operating System?
```
An Operating System is an interface between computer hardware and computer users.
OS is software which manages the hardware
It performs tasks like memory management, file management, process management, controlling peripheral devices such as disk drives and printers, and handling input and output. 

Example: Linux Operating System, Windows Operating System, etc.

note :
System Software: OS , DRIVERS
Application Software: Text editor, Media player

Hardware consist of cpu, memory, i/o devices

EX: source code is usaully store in secondary memory - compile obj code will be stored in main memory) 
every process is executed by processor i.e cpu, with the help of os
cpu acccess everything from mai memory
```

Why is the operating system important?
```
Backbone of any computer system.
It manages hardware resources, allowing different programs to run smoothly and efficiently.
Without an operating system, a computer would not function because there would be no interface for the user to interact with the hardware. 
The OS ensures that all processes and applications get the necessary resources and helps prevent conflicts by managing tasks effectively.
```

List some of the standard services by OS?
```
Some of the standard services by OS are :

USER SERVICES: 
User interface
Program execution
I/O operations 
File-system manipulation 
Communications
Error detection

SYSTEM SERVICES:
Resource allocation
Accounting
Protection and security
```

functions of an operating system. 
```
Memory Management
Processor Management
Device Management
File Management
Security
Control over system performance
Job accounting
Error detecting aids
Coordination between other software and users

Memory Management 
Allocates and deallocates memory space as needed by programs.
It refers to the management of Main Memory or Primary Memory, an extensive array of words, each having its address.
Main memory provides fast storage that can be accessed directly by the CPU. 

Some of its activities are:
It keeps track of the main memory, i.e., what part is in use by whom and what part is not in use. 
When a process requests, it allocates the memory to it.
When a process no longer needs the memory, it de-allocates the memory.
 
Processor Management 
Handles process creation, scheduling, and termination.
It helps the OS to decide which process gets the processor when and for how much time.

Some of its activities are: 
It keeps track of the processor and status of the process. 
When a process requests, it allocates the processor (CPU) to it.
When a process no longer needs the processor, it de-allocates it.
 
Device Management 
Manages hardware devices and coordinates their input/output operations.
An OS manages device communication via their respective drivers.

Some of its activities are:  
It keeps track of all devices.
Efficiently allocates the device.
De-allocates devices.

File Management 
Manages files and directories, providing access to the storage system.
A file system is usually organized into directories for easy navigation and usage. These directories may contain files and other directories.

Some of its activities are: 
It keeps track of location, information, uses, status, etc. The collective facilities are often known as the file system.
 
Decides who gets the resources.
 
Allocates the resources.
 
De-allocates the resources.
 
Security − It prevents unauthorized access to programs and data. 

Control over system performance − It records delays between the request for a service and the response from the operating system. 

Job accounting − It keeps track of resources and time used by various users and jobs. 

Error detecting aids − It helps in detecting the production of dumps, traces, error messages, and other debugging and error detecting aids. 

Coordination between other software and users − It coordinates and assigns compilers, assemblers, interpreters, and other software to the multiple users of the computer systems.

```

What are the different operating systems?
```
Batched operating systems
Multiprogrammed operating systems
Multitasking operating systems
Multiprocessing operating systems
Distributed operating systems
Time-Sharing operating systems
Real-time operating systems
```

What is a kernel in an OS?
```
Part of os
Kernel is a core component of an operating system (OS) that acts as a bridge between software applications and the hardware of a computer. It is responsible for managing system resources, such as the CPU, memory, and input/output devices

kernel is the first part of the operating system to load into memory after the system starts, even before the rest of the operating system loads. 
kernel remains in memory until the operating system shuts down or the computer is rebooted. 

kernel divides memory into two parts:

Kernel Space: Where the kernel operates. It has full access to hardware and controls system functions. Only the kernel can run here.

User Space: Where user applications run. These apps can't access hardware directly and must ask the kernel for services.
```

Define a process.
```
An executing program in an OS is known as a process. 
```

What are the different states of a process?
```
A list of different states of process:
New Process
Running Process
Waiting Process
Ready Process
Terminated Process
```
What is the difference between process and program?
Answer: A program is a set of instructions that tells the computer what to do. A process is a program that is currently running. In other words, a program is a static entity, while a process is a dynamic entity.
