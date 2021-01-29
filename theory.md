Exercise 1 - Theory questions
-----------------------------
 
 ### What is the difference between concurrency and parallelism?
 > Concurrency is the act of managing and running multiple computations at the same time, but not simultaneously, which means that multiple tasks can not be executed at the same time. The control switches between computations. Parallelism is the act of running multiple computations simultaneously. More than one computation could be running at the same time. This requires for example a multiple processor.

 
 ### Why have machines become increasingly multicore in the past decade?
 > A multi-core processor is a processor on a single integreted circuit with two  or more seperate processing units (cores), which leads to more executed instructions at the same time. The single processor with multiple cores results in a processor who can preform many tasks at the same time, and thereby increase overall speed for programs. Todays technology is moving forward in fast speed, along with users expectations. This means that we want better, smaller, lighter, and faster computers. By compressing many cores on a single chip, you will get a smaller unit with much power. This is one of the multicores advantages, higher performance at lower energy.
 
 ### Why do we divide software (programs) into concurrently executing parts (like threads or processes)?
 (Or phrased differently: What problems do concurrency help in solving?)
 > The advantage of dividing programs into concurrently executing parts is that it increases program "workflow". For example, if you have parallel execution of a concurrent program it will allow the number of tasks completed in a given time to increase significantly.
 
 ### Does creating concurrent programs make the programmer's life easier? Harder? Maybe both?
 (Come back to this after you have worked on part 4 of this exercise)
 > *Your answ
 
 ### What is the conceptual difference between threads and processes?
 > A process is a program in execution, and a thread is a segment of a process. 
 
 ### Some languages support "fibers" (sometimes called "green threads") or "coroutines"? What are they?
 > "Fibers" are a lightweight thread of execution similar to OS threads. They are cooperatively scheduled, which means that they will allow another fiber to run. Coroutine is something that is pretty similar, and they are not that unlike, accept from coroutines are usually a language-level construct, while fibers is a system-level concept. 
 
 ### What is the Go-language's "goroutine"? A C/POSIX "pthread"?
 > Goroutine is a lightweighted thread of execution which is managed by the Go runtime. Accomplishing different tasks using multiple Goroutines enables concurrency in the application. POSIX threads are a standards based thread API for C and C++. It allows one to spawn a new concurrent process flow, and is effective on multicore systems. 
 
 ### In Go, what does `func GOMAXPROCS(n int) int` change? 
 > It sets the maximum number of CPUs that can be executing simultaneously and returns the previous setting. If n>1. 


 
 
 
 
