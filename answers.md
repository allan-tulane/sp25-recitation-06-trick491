# CMPS 2200 Recitation 06
## Answers

**Name:**_________Patrick JOhnson________________
**Name:**___________n/a______________


Place all written answers from `recitation-07.md` here for easier grading.

2)
base: W(0) = W(1) = 1; recursive: W(n) = W(n - 1) + W(n - 2) + 1; solution: W(n) = Θ(2ⁿ)

3)
base: S(0) = S(1) = 1; recursive: S(n) = max(S(n - 1), S(n - 2)) + 1; solution: S(n) = Θ(n)

4)
The function values resemble a Fibonacci-like sequence. The entry counts[i] represents how many times fib_recursive(i, counts) is called when computing fib_recursive(n, counts).

6)
The maximum number of times fib_top_down(i) is called for any i is once, thanks to memoization; work: O(n); span: O(n)

8)
Each value Fi is computed at most twice, due to the update: fibs[i] = fibs[i - 1] + fibs[i - 2]; work: O(n); span: O(1)
