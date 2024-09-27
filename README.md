# Plus-2-or-Minus-1

Sharad has a number X whose value is initially 0. In one move, he can do one of the following:
Increment X by 2 i.e. X: = X + 2
Decrement X by 1 i.e. X: = X − 1
He can perform at most Y moves. He wants to determine how many distinct values can X have after performing at most Y moves.

t = int(input())
for _ in range(t):

    n = int(input())
    print(n * 3 + (n == 0))
