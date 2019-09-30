# MEMO

## Dynamic Programming

### Maximum Subarray( [53. Maximum Subarray](https://leetcode.com/problems/maximum-subarray/) )

1. 普通 2 元数列 可以获取所有 subarray 的和，然后取最大

2. Maximum Product Subarray( [152. Maximum Product Subarray](https://leetcode.com/problems/maximum-product-subarray/) )
   和最大和的差别是， 最大乘积的时候 负数的影响， 如果不考虑负数的影响的话， 解法就是一样的
   所以只需要把情况分为两种来讨论，正数的时候和最大和一样， 负数的时候，只需要乘以前面的最小值就OK

### Path

1. Unique Path( [62. Unique Paths](https://leetcode.com/problems/unique-paths/) )

   普通 2 元数列 f(i,j) = f(i-1,j) + f(i, j-1)

2. Unique Path II( [62. Unique Paths II](https://leetcode.com/problems/unique-paths-ii/) )

   普通 2 元数列, 追加障碍位置，到达障碍位置的通路数为零，其他都是一样

3. Minimum Path Sum( [64. Minimum Path Sum](https://leetcode.com/problems/minimum-path-sum/) )

   普通 2 元数列，f(i,j) = Min(f(i-1,j),f(i,j-1)) + nums[i,j]

4. Triangle Minimum Path( [120. Triangle](https://leetcode.com/problems/triangle/) )
   f(I,j) =Min(f(i-1,j),f(i-1,j-1) + triangle[i][j]

5. 变形Path, 从一个字符串转化为另一个字符串的最短路径( [72. Edit Distance](https://leetcode.com/problems/edit-distance/) )
   f(i,j) 把前面i个字符转化为目标字符串的前面j个字符的最短路径
   两种情况：1， A[i] == B[j],   2 A[i] != B[j]

### Find Path From Word

1. Word Ladder II 





### MAX AREA

1. 最大长方形( [85. Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/) )
   从一个二元数组中，找到最大的只包含1的长方形
   f(i,j) =  



5. Climbing Stairs( [70. Climbing Stairs](https://leetcode.com/problems/climbing-stairs/) )

普通一元数列, f(n) = f(n-1) + f(n-2)
