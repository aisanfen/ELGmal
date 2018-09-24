下面的描述以EIGamal加密算法为例，签名算法可以参考相关要求即可。
功能要求:
（1）产生一个奇数p，判断是否是素数。素数要求介于214-215。先用小于20的素数去试除，再使用Miller-Rabin概率检测算法进行检测，
（2）求得模p的一个原根，要求原根的值介于25-210；
（3）设定用户的私钥x介于29-211，使用平方乘算法计算得到用户的公钥y.
（4）设默认要加密的明文为32655，加密时用户选择的随机数k介于25-27，使用模重复平方法对该明文进行加密。
（5）用平方乘算法对第（4）加密后的密文进行解密。
输出要求：
（1）输出奇数的产生过程，用函数实现产生满足要求的奇数；
（2）输出用小素数试除的判断过程，并输出每次试除之后的余数，用函数实现一次试除并返回试除之后的余数；
（3）Miller-Rabin概率检测算法运行5次，输出检测过程及结果。用函数实现一次Miller-Rabin概率检测算法并返回检测结果；
（4）如果不是奇素数，输出下一个奇数产生的规则；
（5）输出产生模p的一个原根的过程；
（6）输出选择的私钥x，并输出使用平方乘算法计算得到用户的公钥y的过程；
（7）输出用户选择的随机数k，以及使用模重复平方法对该明文进行加密的过程。
