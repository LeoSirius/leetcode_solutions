### 思路1 贪心

当nums[i-1] > nums[i]时，就需要改其中一个数，让两个数一样大。

最好是改i-1，因为改大会影响后面。

三种情况

1. 第一个数，不管后面什么情况，都把第一个数改成和第二个数一样就行
4 2 3
4 3 2

2. 

2 7 4 

这时改7为4

3.

4 7 1

这时改7为1没用，只能改1为7
