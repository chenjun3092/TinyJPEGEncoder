tiny_jpeg.h
===========

A header-only public domain implementation of Baseline JPEG compression.

Features:
---------

- stb-style header only library.
- Does not do dynamic allocations
- Simple API:
    - 2 API calls.
    - 3-value compression quality: 3 (best quality), 2 (Very good), 1 (Noticeable artifacts, best compression)
- Public domain


---
1. 加入了自己的一些注释
2. 加入cmake编译
3. 添加测试文件夹img
4. 添加JFIF的参考资料[Matlab JPEG详细介绍](http://blog.csdn.net/lg1259156776/article/details/50755525)，比较详细准确地说明整个编码也即代码实现过程
