| Q No. | Problem                                   | Complexity / Answer                    | Short Explanation                                                                   |
| ----- | ----------------------------------------- | -------------------------------------- | ----------------------------------------------------------------------------------- |
| Q1    | T(n) = T(n/2) + T(2n/5) + 7n              | **Θ(n)**                               | Using Akra-Bazzi, recursive fractions sum to less than 1, so linear work dominates. |
| Q2    | T(n) = aT(n/b) + f(n)                     | **a = b and f(n) = Θ(n)**              | Master Theorem Case 2 gives Θ(n log n).                                             |
| Q3    | Check if array is sorted using one pass   | **Θ(n)**                               | Compares adjacent elements once.                                                    |
| Q4    | 1³ + 2³ + ... + n³                        | **Θ(n⁴)**                              | Sum of cubes = (n(n+1)/2)².                                                         |
| Q5    | Given nested loops with p and q           | **Θ(n log log n)**                     | p = Θ(log n), inner loop = Θ(log log n), outer loop = Θ(n).                         |
| Q6    | for(i=n;i>0;i/=2) <br> for(j=0;j<i;j++)   | **Θ(n)**                               | Geometric series: n + n/2 + n/4 + ... = 2n.                                         |
| Q7    | for(i=1;i<=n;i++) <br> for(j=1;j<=i;j++)  | **Θ(n²)**                              | Total iterations = 1+2+...+n.                                                       |
| Q8    | fun(n/2); fun(n/2);                       | **Θ(n)**                               | Recurrence: T(n)=2T(n/2)+1.                                                         |
| Q9    | Fibonacci Recursion                       | **Θ(1.618ⁿ) ≈ O(2ⁿ)**                  | Recursive tree grows exponentially.                                                 |
| Q10   | Arrange Growth Rates                      | **n log n < n^(3/2) < n^(log₂n) < 2ⁿ** | Increasing order of growth.                                                         |
| Q11   | T(n)=T(n−1)+1                             | **Θ(n)**                               | Adds constant work n times.                                                         |
| Q12   | T(n)=T(n−1)+n                             | **Θ(n²)**                              | Sum of first n numbers.                                                             |
| Q13   | T(n)=2T(n−1)+1                            | **Θ(2ⁿ)**                              | Recursive calls double at each level.                                               |
| Q14   | T(n)=T(n/2)+1                             | **Θ(log n)**                           | Problem size halves each step.                                                      |
| Q15   | for(i=1;i<=n;i*=2) <br> for(j=1;j<=n;j++) | **Θ(n log n)**                         | Outer loop = log n, inner loop = n.                                                 |
