### 思路1

我们直接用比特位来存放四种字符，用字节太浪费空间。这里四个字符，用2的比特位就可以表示。

四个字符，用两个比特位就可以表示所有可能的情况。10个字符，用20个比特位就可以表示所有情况，

10个字符就是20个比特位，，共`2*20-1`种可能性。