#分治与递归
##递归的条件
关键：寻找子问题
子问题与原始问题相同规模更小；有一个出口
##分治法
把一个复杂问题分解成多个子问题，子问题间相互独立，且与原问题相似
##区别
递归是串行，分治是并行


### 知识
#杨辉三角
杨辉三角实际上就是二项式定理里的系数，
　　第n行对应(x+1)^(n-1)
　　第m列就是(x+1)^(n-1)展开式中x^(m-1)的系数
　　所以，根据排列组合相关知识，
　　第n行m列元素应该为：
　　C(n-1,m-1)=(n-1)!/[(m-1)!(n-m)!]
　　(其中!表示阶乘，n！=n*(n-1)*...*2*1)
　　如仍有疑惑，欢迎追问。  祝：学习进步！