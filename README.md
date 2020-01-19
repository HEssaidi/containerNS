# containerNS
Container using namespaces
Hello everybody ; this is my project about containers using namespaces concept.
There is no such thing as a "linux container" in the kernel. A container is a userland concept. 
So good luck with it...



Concept:
We create a child process in a new namespace (with PIDs, network, mounts, IPC and UTS)
Run this program using sudo – you will get a different shell, file system and network





The first file .txt : is a description of our clone function and its flags 
Second file .c : tests for clone function using each flag ; when you run each programm you should add the command as specified 
                 after running the programm (./programm)
Third fie .c : the entire programm adding a function that will add an ip address to our container , and he can ping on his 
               parent process using the second ip address.
