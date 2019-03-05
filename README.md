authers:
Rivka Revivo

Ron Mor

Sela Goldenberg

# Bash-debug
Task 1 - Bash cpp

first task in cpp ariel university.

BasicCheck used to debug c++ program for memory leak and Thread races.

BasicCheck recive 3 paramaters:
1.folder where the Makefile is
2.The Program
3.The Program Parameters

The Program will Print Compilation PASS/FAIL for the Compilation success.
if The Compilation succesed then we run valgrind and helgrind and print:
Memory leaks PASS/FAIL - for valgrind
thread race PASS/FAIL - for helgrind

The Program exit with Code between 0 and 7
where 0 is everything work.
The MSB represent the Compilation success (0 work / 1 fail)
The bit after represent the valgrind success.
The LSB represent the helgrind success.
