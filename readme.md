1.system calls currently running process and parent display same.\
Algorithm:-\
step1:Include the header files like stdio.h,stdlib.h,unistd.h,sys/types.h\
step2:-check if forking is successfull\
step3:-GetprocessID's(use getpid())\
step4:-get the parent id(use getpid())\
step5:-Display process IDs(print process ID and parent processID)\
step6:-End Algorithm\

2.systemcall to copy content from one file to another file\
Algorithm:-\
step1:-Include libraries(headerfiles like stdio.h,stdlib.h,fcntl.h,unistd.h)\
step2:-open source and destination files\
step3:-use two files one for reading and for writing\
step3:-check if files are opened successfully\
step4:-Read content from source file\
step5:-copy the contents to the file\
step6:-close 2 file(use 'close()')\
step7:-End of Algorithm\

3.Design CPU scheduling algorithm with c using FCFStechnique\
a.All process are activated time 0\
b.Assume no process in I/O devices\
Algorithm:-\
step1:-Include libraries(header file like stdio.h)\
step2:-get input from the user for no:of processors and burst time\
step3:-use for loop\
step4:-calculate waiting time and turnaroundtime by using formula\
step5:-calculate average waiting time and turnaroundtime\
step6:-display the data\
step7:-End of Algorithm\

4.ccode for scheduling select waiting process with executiontime to execute next\
Algorithm:-\
step1:-Input given by user wih n number of process\
step2:-sort process based on burst time\
step3:-Initialise variables(current time,completed process)\
step4:-process scheduling\
step5:-display output\
step6:-End of program\

5.scheduling program with c select waitingprocess to execute next\
Algorithm:-\
step1:-Input(enter number of process)\
step2:-sort process based on priority(highest to lowest)\
step3:-Initialize variables(currenttime,completedprocess)\
step4:-process scheduling\
step5:-display the output\
step6:-End of program\

6.c program to implement preemptive priority scheduling algorithm\
Algorithm:-\
step1:-Input(enter number of process)\
step2:-Initialise variables\
step3:-process scheduling\
step4:-display output\
step5:-End of program\

7.cprogram to implement nonpreemptive sjf algorithm\
Algorithm:-\
step1:-Input(Enter number of process)\
step2:-sort the process based on their burst time in ascending order\
step3:-Initialisation step4:-for each process from 1 to n\
step5:-calculate average waiting time\
step6:-calculate average turnaroundtime\
step7:-End of program\

8.cprogram to simulate roundrobin scheduling algorithm with c\
Algorithm:-\
step1:-Input(number of processes)\
step2:-Initialise an empty queue to store process\
step3:-while there are processed in queue or any process has remaining bursttime\
step4:-End of program\

11.c program for multithreading Algoritm:-\
step1:-Include necessary header file\
step2:-Define the threadfunction
step3:-create threads\
step4:-join threads\
step5:-compile and run program\
step6:-End of program\

12.cprogram for Dining Philosophers problem\
Algorithm:-\
step1:-Initialization\
step2:-philospher behaviour\
step3:-Handling forks\
step4:-synchronization\
step5:-Implementation using loop\
step6:-End of program\

13.c program for various memory allocation strategies\
Algorithm:-\
step1:-Input(enter memorysize)\
step2:-Initialisation(set found flag to 0)\
step3:-loop through memoryblocks\
step4:-if 'found'flag is 1,memory allocated successfully\
step5:-if 'found'flag is 0,not enough space is available for allocation\
step6:-End of program\

14.c program for organisefile using singlelevel directory\
Algorithm:-\
step1:-file structure\
step2:-Directory structure(not needed for single level directory)\
step3:-operation(like create newfile,delete file,list file,search file,Exit)\
step4:-Enter the operation to perform step5:-file can be created ,listed,updated it continue till exit\
step6:-End of program\

15.c program to organize file using two level directory structure\
Algorithm:-\
step1:-file structure(structfile contain attributes suchas name,size)\
step2:-struct directory(directory attribute suchas name,list of files)\
step3:-Enter directoryname and parent directory\
step4:-perform operation(create directory,create file,delete file,listfile,exit)\
step5:-Initialize filesystem\
step6:-End of program\

16.c program for implementing random access file for processing employee details\
Algorithm:-\
step1:-Include necessary headerfiles\
step2:-Define and create a new employee structure\
step3:-open or create random access file\
step4:-Implement functions for various operations\
step5:-Implement main menu loop\
step6:-close file and exit\
step7:-compile and run program\
step8:-handle errors and edge cases\
step9:-test the program\
step10:-End of program\

17.deadlock avoidance concept by simulating bankers algorithm with c\
Algorithm:-\
step1:-Include necessary headerfiles\
step2:-Define constants and initialize the requried variables\
step3:-Declare global variables\
step4:-Initialise all the requried functions\
step5:-Request resource function\
step6:-safety check function\
step7:-End of program\

18.c program to simulate producer consumer problem using semaphores\
Algorithm:-\
step1:-Include necessary header files\
step2:-Define all the requried constants\
step3:-And declare all global variables which are necessary\
step4:-Initialise semaphores\
step5:-Define producer function\
step6:-End of program\

19.cprogram to implement synchronization using mutex locks\
Algorithm:-\
step1:-Include necesssary headerfiles\
step2:Declare all global variables which are necessary\
step3:-Initialise mutex\
step4:-Define first thread function according to the user\
step5:-Define second thread function according to the user\
step6:-handling errors and edge cases\
step7:-End of program\

20.program to simulate reader-writer problem using semaphores\
Algorithm:-\
step1:-Include number of active readers\
step2:-simulate work\
step3:-block writers if first reader\
step4:-unblock writers if lastreader\
step5:-End of program\

21.Algorithm for cprogram to implement worst fit algorithm of memory managment\
Algorithm:-\
step1:-Include size of memory block\
step2:-flag to indicate if block is allocated\
step3:-Initiate memory blocks\
step4:-calculate for the worst fit among the given\
step5:-allocate memory from process\
step6:-End of program\

22.Algorithm for cprogram to implement best fit algorithm of memory managment\
Algorithm:-\
step1:-Include size of memory block\
step2:-flag to indicate if block is allocated\
step3:-Initiate memory blocks\
step4:-calculate for the best fit among the given\
step5:-allocate memory from process\
step6:-End of program\

23.Algorithm for cprogram to implement first fit algorithm of memory managment\
Algorithm:-\
step1:-Include size of memory block\
step2:-flag to indicate if block is allocated\
step3:-Initiate memory blocks\
step4:-calculate for the first fit among the given\
step5:-allocate memory from process\
step6:-End of program\

24.Algorithm for cprogram to calculate and print if the byte size is present\
Algorithm:-\
step1:-Include all the header files requried\
step2:-Initialize all the variables and the characters requried\
step3:-Get the inout in the code\
step4:-Calculate the bytes value of the given input\
step5:-if the bytes values is greater than 0 display the values of bytes and the input data\
step6:-End of program\
