Project instructions: The goal of this project is to simulate the paging scheme in memory management. The tester code is provided in Factory.java and MemoryThread.java. As you can see, 5 threads are created and each requests for a certain number of pages (simulates loading a new process into memory), then accesses a certain page (simulates referencing a logical address), and then releases the requested memory (simulates terminating a process).

The program then through the PhysicalMemory class allocates that memory to the paging table with a set frame size. 

This program utilizes semaphores to aquire and release the lock on the paging table to ensure that no thread accesses the same frame of memory as another thread. 

While this was a group project it was highly collaborative and each individual looked over the code. For this project we recieved 99/100 and we were responsible for the Factory and PhysicalMemory classes in their entirety. 

Ahsif Safdar
Ahsif.safdar@gmail.com
Thank you for reading!