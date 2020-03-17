foobar:~/ guest$ request
You are about to begin a time-limited challenge which you will have 48 hours to complete.
If you do not have time for the challenge now, you may sign in to save your place and return later to request the challenge.
Do you wish to proceed and start your first challenge?
[Y]es or [N]o: y
Requesting challenge...
Commander Lambda sure is a task-master, isn't she? You're being worked to the bone!
New challenge "Re-ID" added to your home folder.
Time to solve: 48 hours.

foobar:~/ rizwana.cty$ ls
re-id
journal.txt
start_here.txt

foobar:~/ rizwana.cty$ cat journal.txt
Success! You've managed to infiltrate Commander Lambda's evil organization, and finally earned yourself an entry-level position as a Minion on her space station. From here, you just might be able to subvert her plans to use the LAMBCHOP doomsday device to destroy Bunny Planet. Problem is, Minions are the lowest of the low in the Lambda hierarchy. Better buck up and get working, or you'll never make it to the top...

Commander Lambda sure is a task-master, isn't she? You're being worked to the bone!
foobar:~/ rizwana.cty$ cat start_here.txt
Type request to request a challenge. Type help for a list of commands.
foobar:~/ rizwana.cty$ cat re-id
cat: re-id: Is a directory
foobar:~/ rizwana.cty$ cd re-id
foobar:~/re-id rizwana.cty$ ls
Solution.java
constraints.txt
readme.txt
solution.py
foobar:~/re-id rizwana.cty$ cat constraints
cat: constraints: No such file or directory
foobar:~/re-id rizwana.cty$ cat constraints.txt
Java
====
Your code will be compiled using standard Java 8. All tests will be run by calling the solution() method inside the Solution class

Execution time is limited.

Wildcard imports and some specific classes are restricted (e.g. java.lang.ClassLoader). You will receive an error when you verify your solution if you have used a blacklisted class.

Third-party libraries, input/output operations, spawning threads or processes and changes to the execution environment are not allowed.

Your solution must be under 32000 characters in length including new lines and and other non-printing characters.

Python
======
Your code will run inside a Python 2.7.13 sandbox. All tests will be run by calling the solution() function.

Standard libraries are supported except for bz2, crypt, fcntl, mmap, pwd, pyexpat, select, signal, termios, thread, time, unicodedata, zipimport, zlib.

Input/output operations are not allowed.

Your solution must be under 32000 characters in length including new lines and and other non-printing characters.
foobar:~/re-id rizwana.cty$ cat readme.txt
Re-ID
=====

There's some unrest in the minion ranks: minions with ID numbers like "1", "42", and other "good" numbers have been lording it over the poor minions who are stuck with more boring IDs. To quell the unrest, Commander Lambda has tasked you with reassigning everyone new, random IDs based on her Completely Foolproof Scheme. 

She's concatenated the prime numbers in a single long string: "2357111317192329...". Now every minion must draw a number from a hat. That number is the starting index in that string of primes, and the minion's new ID number will be the next five digits in the string. So if a minion draws "3", their ID number will be "71113". 

Help the Commander assign these IDs by writing a function solution(n) which takes in the starting index n of Lambda's string of all primes, and returns the next five digits in the string. Commander Lambda has a lot of minions, so the value of n will always be between 0 and 10000.

Languages
=========

To provide a Java solution, edit Solution.java
To provide a Python solution, edit solution.py

Test cases
==========
Your code should pass the following test cases.
Note that it may also be run against hidden test cases not shown here.

-- Java cases --
Input:
Solution.solution(0)
Output:
    23571

Input:
Solution.solution(3)
Output:
    71113

-- Python cases --
Input:
solution.solution(0)
Output:
    23571

Input:
solution.solution(3)
Output:
    71113

Use verify [file] to test your solution and see how it does. When you are finished editing your code, use submit [file] to submit your answer. If your solution passes the test cases, it will be removed from your home folder.