# Topic: Running Times
## Algorithm Analysis
- Space Efficiency: Somewhat Important
- Time Efficiency: **SUPER IMPORTANT!**

## Running Time 
`Running Time = T(n)`
- N is usually the size of the input:
    - Number of items to sort
    - Number of items to search
    - Size of objects

- Cases:
    - Worst Case (Most Common)
    - Average Case
    - Amortized
    - Best Case

- Factors To Ignore:
    - Small Input Size
    - Speed of the Machine

## Big O
### Formula
$$n \ge n_0, f(n) \le g(n)$$

## Models of Computation
- A mathematical model that represents the actual computers on which algorithms will be run
- Provides a way to analyze algorithms without having to actually run them
- Examples:
    - Turning Machine (TM)
    - Random Access Machine (RAM)
    - Parallel Random Access Machine (PRAM)

- RAM: Rules for running-time analysis
    1. Each simple arithmetic operation takes constant time
    2. Each assignment takes constant time
    3. Running time of a sequence is the sum of each statement
    4. Running time of an if is the sum of all sections
    5. Running time of a loop is iterations times body
    6. Nested loops are Rule 5 from inside out
