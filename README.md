# 4sum
First, sort the array. Two nested loops fix numbers i and j, skipping duplicates. A two-pointer approach (l, r) finds the remaining two numbers. We use long long for sums to prevent overflow and skip duplicates to ensure unique quadruplets. Time: $O(n^3)$.
