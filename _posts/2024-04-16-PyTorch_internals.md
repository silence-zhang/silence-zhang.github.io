# Pytorch Internals

source: <https://pytorch.org/tutorials/beginner/former_torchies/tensor_tutorial.html>

Here's the table of contents:

- TOC
{:toc}

## Tensor

The tensor is the central data structure in PyTorch. its an n-dimensional data structure containing some sort of scalar type, e.g., floats, ints, et cetera.

![p1](/images/WX20240416-160518@2x.png)

### Stride

Stride are actually one of the distinctive features of PyTorch. It is a way to represent the memory layout of a tensor.

![p2](/images/WX20240416-161014@2x.png)

Stride is the jump necessary to go from one element to the next one in the specified dimension dim. 

![p3](/images/WX20240416-161902@2x.png)

```python
import torch
>>> x = torch.tensor([[1, 2, 3, 4, 5], [6, 7, 8, 9, 10]])
>>> x.stride()
(5, 1)
>>> x.stride(0)
5
>>> x.stride(-1)
1
```
