01-MNIST
====
手書き文字(0~9)認識

## Description
### 使用データセット
[MNIST](http://yann.lecun.com/exdb/mnist/)

### 使用ネットワーク
[Lenet](http://yann.lecun.com/exdb/publis/pdf/lecun-01a.pdf)[1]  

### 参考文献
[1] Y. LeCun, L. Bottou, Y. Bengio, and P. Haffner, "Gradient-Based Learning Applied to Document Recognition," Proceedings of the IEEE, november, 1998.

## Usage
```
$ python main.py
```

### 動作環境(確認済み)
accuracy 99.0% 
#### on cpu
OS macOS High Sierra
プロセッサ 2.5 GHz Intel Core i7  
メモリ 8 GB 2133 MHz LPDDR3   
elapsed time 0h 2m 45s  

#### on gpu
OS: Ubuntu 16.04  
プロセッサ Intel(R) Core(TM) i7-6850K CPU @ 3.60GHz  
グラボ GeForce GTX 1080 × 2  
cuda 8.0  
cudnn 5.1  
accuracy 99.0%  
elapsed time 0h 0m 26s  

## Author
chatflip
[[github](https://github.com/chatflip)]
[[Qiita](https://qiita.com/chat-flip)]

This code borrows from [pytorch/example](https://github.com/pytorch/examples)  