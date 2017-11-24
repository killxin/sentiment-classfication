本代码参考自博客["Implementing a CNN for Text Classification in Tensorflow"](http://www.wildml.com/2015/12/implementing-a-cnn-for-text-classification-in-tensorflow/)

以下内容改编自原始项目的readme文件

It is slightly simplified implementation of Kim's [Convolutional Neural Networks for Sentence Classification](http://arxiv.org/abs/1408.5882) paper in Tensorflow.

## Requirements

- Python 3
- Tensorflow > 0.12
- Numpy

## Training

```bash
./train.py
```

## Evaluating

```bash
./eval.py --checkpoint_dir="./runs/1459637919/checkpoints/"
```

Replace the checkpoint dir with the output from the training.


## References

- [Convolutional Neural Networks for Sentence Classification](http://arxiv.org/abs/1408.5882)
- [A Sensitivity Analysis of (and Practitioners' Guide to) Convolutional Neural Networks for Sentence Classification](http://arxiv.org/abs/1510.03820)
