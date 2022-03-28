# cs475-proj2

Xinu Project 2
https://davidtchiu.github.io/teaching/cs475/proj2/

Jacob Ota and Langston Aron

The priority of every process in the queue increases by 1 every time enqueue() is called when AGING is TRUE. By putting it in enqueue it will run on a resched and a ready call which will in turn make all the processes increase by 1 when ready is called and all processes except for the nullproc process and the process selected for schedulking in the resched call.
