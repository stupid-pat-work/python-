# python-
个人python小程序练习和笔记
习题一

#有0、1、2、3、4、5个数字，能组成多少个互不相同且无重复数字的三位数？都是多少？#

for i in range(1,6):
    for j in range(0,6):
        for k in range(0,6):
            if (i != j) and (j != k)  and (k != i):
                print(i,j,k)
