1- Suppose you have a sorted list of 128 names, and you’re searching through it using binary search. What’s the maximum number of steps it would take?
    Binary search bad cases is resolved in Log n. "N" in this case is 128, the equivalent of log2 128 is 2^7, so the number of the steps is 7.

2- Suppose you double the size of the list. What’s the maximum number of steps now?
    The maximum number of steps is 8 because it's the same of 2^7 + 2^1.

3- You have a name, and you want to find the person’s phone number in the phone book.
    O(log n)

4- You have a phone number, and you want to find the person’s name in the phone book. (Hint: You’ll have to search through the whole book!)
    O(n)

5- You want to read the numbers of every person in the phone book.
    O(n)

6- You want to read the numbers of just the As.
    O(n), the As gonna be on the start.

    