# Intel-Processor
x86 implementation of Intel Processor, capable of loading data and doing simple math
This was a group project, but I created the fetch and decode processes. The fetch process revolves around digesting the Y86 code, and making sure that the proper bits get sent to the right areas. The most vital part to the fetch unit is arguably the PC Incrementer, which makes sure that all the commands are logically split, so that one command is executed at a time.
