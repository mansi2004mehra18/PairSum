# PairSum

brute force - can be applied in any cases, since it is giving all the possible pairs.
code of brute force for both the pair sum is excatly same.\

optimized approch for both the cases is 2 pointer approach.

Pair Sum - 1 [Sorted]

Find if any pair in a Sorted ArrayList has a target sum. 
[//imp thing ArrayList is in sorted state]
list = [1,2,3,4,5,6]
target = 5 

approach 
1: BRUTE FORCE  {
    all possible pairs are calculated [O(n^2)]
}
2: 2 POINTER {
    O(n)

    case1: lp-num + rp-num == target
        return true
    case2 : lp-num + rp-num < target
        lp++
    case3: lp-num + rp-num > target
        rp--
}


Pair Sum - 2 [Sorted & Rotated]

Find if any pair in a Sorted & Rotated ArrayList has a target sum. 
list = [11, 15, 6, 8, 9, 10], target = 16
