# LeetCode
这里有我关于LeetCode部分题型的心得
*******************************************************************************************************
双指针（two pointers）要在有序数组上（多为升序）操作。//sort（）；
可以让查找时间复杂度降次
即 有序的数据存储可以提高查找速度（二分法）
可参考
https://leetcode.com/explore/learn/card/array-and-string/205/array-two-pointer-technique/1156/
*******************************************************************************************************
对于查找时 使用的for循环与while循环，根据条件设置循环终止点，可以在时间复杂度难以改善时，适当提高查找效率。
如 twoSum threeSum中的 sums[i]>target,sums[i]+sums[i+1]>target（前提 要对sums排序）等。

*******************************************************************************************************
在测试程序时，一定要考虑极端情况，如输入指针为空，输入值溢出上下限
循环或递归时同时考虑常规情况与边界情况
如二分法 既要考虑left与right相距较远的常规情况，也要考虑left与right相差1的特殊情况。

*******************************************************************************************************
