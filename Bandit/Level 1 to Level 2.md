这里就开始比较tricky了。
Linux是可以把`-`作为文件名的，但是cat命令会把`-`视作标准输入的代名词[1]。

解决办法是写`./-`或者写全路径`/home/bandit1/-`。

# Reference

[1] https://unix.stackexchange.com/questions/16357/usage-of-dash-in-place-of-a-filename