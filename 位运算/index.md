### 位运算

从现代计算机中所有的数据二进制的形式存储在设备中。即 0、1 两种状态，计算机对二进制数据进行的运算(+、-、\*、/)都是叫位运算，即将符号位共同参与运算的运算。

位运算符

| 运算符 |                                             含义                                             |
| :----: | :------------------------------------------------------------------------------------------: |
|   \|   |                                 按位 或 ：两位都为 0，才为 0                                 |
|   &    |                                 按位 与 ：两位都为 1，才为 1                                 |
|   ^    |                              按位 异或 ：两位相同为 0，不同为 1                              |
|   ~    |                                按位 取反 ：0 变成 1 1 变成 0                                 |
|   <<   |                               各二进位左移，高位丢弃，低位补 0                               |
|   >>   | 各二进位右移，对无符号数，高位补 0，有符号数，有的补符号位（算术右移），有的补 0（逻辑右移） |

按位与
0 & 1 = 0; 0 & 0 = 0; 1 & 0 = 0; 1 & 1 = 1;

题目：
