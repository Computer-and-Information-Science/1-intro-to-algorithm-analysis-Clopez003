# CISC230 - Chris Lopez

## factorial2.cpp

- input/parameter impacting number of calls:
    - the number passed to the factorial function, or simply put, the number we want to find the factorial of.
- 3 specific examples of input/parameter and number of calls:
    - Input: 1, # of Calls: 2
    - Input: 3, # of Calls: 4
    - Input: 10, # of Calls: 11
- number of recursive calls when input/parameter is *n*
    - Formula: f(n) = n+1

## ireverse2.cpp

- input/parameter impacting number of calls
    - Length of the number, Ex. "123" is n=3 
- 3 specific examples of input/parameter and number of calls
    - Input: 123, # of Calls: 4
    - Input: 12345, # of Calls: 6
    - Input: 123456789, # of Calls: 10
- number of recursive calls when input/parameter is *n*
    - Formula: f(n) = n+1


## sreverse2.cpp

- input/parameter impacting number of calls
    - Length of the string, Ex. "Hello" is n=5
- 3 specific examples of input/parameter and number of calls
    - Input: Hello, # of Calls: 5
    - Input: reverse, # of Calls: 7
    - Input: fibonacci, # of Calls: 9
- number of recursive calls when input/parameter is *n*
    - Formula: f(n) = n

## permute.cpp

- input/parameter impacting number of calls
    - Length of the string, Ex. "abc" is n=3
- 3 specific examples of input/parameter and number of calls
    - Input: ab, # of Calls: 5
    - Input: abc, # of Calls: 16
    - Input: abcde, # of Calls: 326
- number of recursive calls when input/parameter is *n*
    - Formula: f(n) = [ f(n-1) * n ] +1

## tower.cpp

- input/parameter impacting number of calls
    - Number of disks
- 3 specific examples of input/parameter and number of calls
    - Input: 1, # of Calls: 3
    - Input: 2, # of Calls: 7
    - Input: 3, # of Calls: 15
- number of recursive calls when input/parameter is *n*
    - Formula: f(n) = (2^(n+1)) - 1

## fibonacci2.cpp (presented in video lesson)

- input/parameter impacting number of calls
    - amount of fibonacci numbers to be generated
- 3 specific examples of input/parameter and number of calls
    - Input: 1, # of Calls: 1
    - Input: 3, # of Calls: 5
    - Input: 4, # of Calls: 8
- number of recursive calls when input/parameter is *n*
    - Formula: f(n) = 3(n-2) + 2, when n>1 and when n=1, f(1) = 1
