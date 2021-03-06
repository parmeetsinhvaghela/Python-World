[Back](../README.md)

# Multi-Threading/Processing
---

#### What is Thread?
A thread is a separate flow of execution. This means that your program will have two things happening at once. But for most Python 3 implementations the different threads do not actually execute at the same time: they merely appear to.

It’s tempting to think of threading as having two (or more) different processors running on your program, each one doing an independent task at the same time. That’s almost right. The threads may be running on different processors, but they will only be running one at a time. 

#### Import Thread
```python
from threading import Thread
```

#### What is Process?
Multiprocessing allows you to create programs that can run concurrently (bypassing the [GIL](https://wiki.python.org/moin/GlobalInterpreterLock) ) and use the entirety of your CPU core. Though it is fundamentally different from the threading library, the syntax is quite similar. The multiprocessing library gives each process its own Python interpreter and each their own GIL.

#### Import Process
```python
from multiprocessing import Process
```

