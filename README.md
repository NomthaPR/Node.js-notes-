# Node.js-notes- (Node. Javascript)
Learning about Node.js (Runtime environment)

Node.js doesn't stand for any specific words or phrases. The name "Node.js" was chosen because it evokes the idea of nodes in a network or a graph, 
which reflects its event-driven, non-blocking I/O model. The "js" part refers to JavaScript, the primary programming language used in Node.js development.
Node.js is not a programming laungeage but its  more like an application to use when you want to run Javascript. its actually created to execute javascript code outside the broweser,
be able to open it, read and run it. Node managies the server and increases Javascript capabilities, eliminating time. Node.js is a runtime environment that excutes Javascript. 
Non-blocking refers to a programming paradigm where the execution of certain operations does not halt the execution of the program. In a non-blocking system, 
when an operation is initiated, the program can continue to execute other tasks without waiting for the operation to complete. promoting data-blocking and event-driven models,
eliminating the waiting when running Javascript, it can also create more interactiveness around the fuction buttions or dropdown list. 

In the context of Node.js, it utilizes a non-blocking, event-driven architecture. When Node.js performs/ operations (like reading from a file, making a network request, or querying a database), instead of waiting for the operation to finish, it initiates the operation and registers a callback function to be executed once the operation is complete. This allows Node.js to efficiently handle multiple concurrent operations without getting blocked by I/O-bound tasks. Non-blocking I/O is crucial for building scalable and high-performance applications because it enables the program to handle many connections or operations simultaneously without having to spawn a new thread or process for each one. This approach is particularly useful for applications that need to handle a large number of concurrent requests, such as web servers or real-time applications.


What is the difference between Blocking and Non blocking model:
The defference is how they handle the waiting period while excuting or perfoming the Input and the Output of the operations.

Blocking Model:
In a blocking model, when an I/O operation is initiated, the program halts execution and waits for the operation to complete before moving on to the next task.
During this waiting period, the entire program may be blocked, unable to perform any other tasks. This approach can lead to inefficiencies, especially in scenarios 
where there are multiple I/O operations to be performed concurrently or when an operation takes a significant amount of time to complete.
Traditional synchronous programming languages and frameworks often follow a blocking model by default.

Non-blocking Model:
In a non-blocking model, when an I/O operation is initiated, the program continues execution without waiting for the operation to complete.
Instead of blocking, the program registers a callback function or uses other mechanisms to handle the completion of the operation asynchronously.
This allows the program to perform other tasks while waiting for I/O operations to finish, thus maximizing efficiency and responsiveness.
Non-blocking models are common in event-driven and asynchronous programming paradigms, such as those used in Node.js, where handling multiple concurrent operations efficiently is crucial.


