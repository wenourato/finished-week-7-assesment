|  Insert Time   |  Append Time  | Array Passed  |
|                |               |               |
|   612.5161 ms  |   2.2409 ms   |extraLargeArray|
|                |               |               |
|    6.7313 ms   |   389.3 μs    |  largeArray   |
|                |               |               |
|     150 μs     |   126.8 μs    |  mediumArray  |
|                |               |               |
|      39 μs     |   74.6 μs     |  smallArray   |
|                |               |               |
|      30 μs     |   65.7 μs     |   tinyArray   |
|                |               |               |
|                |               |               |
|                |               |               |
|                |               |               |
|                |               |               |

I beleive that have different run times and append times becasue the passed in arrays have different numbers.  Thhe largest array is coming back with a higher runtime and append time because it is a much larger number.  In the functions, we are looping over 10000 3 seperate times, and that is alot fo the computer to handle.  when passing in a tiny array, the computer can do it almost instantly beccuase even though its looping 3 times, it looking over a fraction of the largest array.