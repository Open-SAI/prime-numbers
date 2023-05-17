# Prime Numbers
Prime Numbers Experiment

This is a programming exercise, developing a simple program to review if a number is prime or not.

## Logic 
A basic number distribution goes like:

|1|2|3|4|5|6|
|7|8|9|10|11|12|
|13|14|15|16|17|18|
|19|20|21|22|23|24|
|25|26|27|28|29|30|
|31|32|33|34|35|36|
|37|38|39|40|41|42|
|43|44|45|46|47|48|
|49|50|51|52|53|54|
|...|...|...|...|...|...|

If cross the 2nd, 3nd, 4nd and 6th columns we can view that they are multiples not prime numbers.

Then we stay with the first and fifth column, where there are many prime numbers, we have the next progression:

A: [7,13,19,25,31,37,43,49,...]

B: [5,11,17,23,29,35,41,47,29,...]

The progression A is in the form 6n+1

The progression B is in the form 6n-1

* Maybe that any P prime number be in the 6n±1 form, but it doesn't mean that all numbers in that form are prime.
* A number can be expressed in the form N = xy, if x or y is greater than the root of N, the other must be less than the root value, then we iterate until the sqrt(N)

## References
* Base Code [https://www.geeksforgeeks.org/prime-numbers/]
* Math review [https://math.stackexchange.com/questions/895992/6n1-and-6n-1-prime-format]

