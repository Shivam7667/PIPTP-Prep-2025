a = 4, b = 3
1. Integer funn(Integer a, Integer b)
2.     if (a > 0)
3.         return funn(a - 2, a + b) + funn(a - 3, a + b) + funn(a - 4, a + b)
4.     Else
5.         a = b
6.         b = a
7.         return a + b
8.     End if
9. End function funn()

answer = 116
