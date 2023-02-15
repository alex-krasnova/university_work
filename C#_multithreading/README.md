## Task Description:

Need to create a program that implements the parallel execution of several tasks, each of which solves some given function. A graph of tasks is given, i.e. the sequence of their execution is determined, as well as the need for parallel execution of some tasks relative to each other. According to the type of graph, some tasks can initiate the execution of others. Tasks can use common (shared) objects and data, therefore, in the designed program, it is necessary to provide synchronization of access to such objects and data.

### Files Created:
Program.cs - the main entry point for the application<br>
TaskThread.cs – abstract thread class<br>
SeeThreads.cs – functions for button clicks, thread classes A - K, thread initialization and start<br>
Locker.cs – lock object class<br>
Logger.cs – class for writing information to a log file<br>

### Screenshots:
initial_form.png<br>
result.png<br>