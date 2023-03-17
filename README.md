# jpeg-python

基于python=3.9与numpy包实现的JPEG，里面还包含编解码器等关键部件。

本代码实现的全过程是这样的：对8x8的图像先每个元素-128，再进行离散余弦变换，再进行量化，再进行zigzag，再进行游程编码，再进行游程解码，再进行反zigzag，再进行反量化，再进行离散余弦变换的逆变换。
