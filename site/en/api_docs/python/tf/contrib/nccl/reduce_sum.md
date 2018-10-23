

page_type: reference


<!-- DO NOT EDIT! Automatically generated file. -->


# tf.contrib.nccl.reduce_sum

``` python
reduce_sum(tensors)
```



Defined in [`tensorflow/contrib/nccl/python/ops/nccl_ops.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.5/tensorflow/contrib/nccl/python/ops/nccl_ops.py).

Returns a tensor with the reduce sum across `tensors`.

The computation is done with a reduce operation, so only one tensor is
returned.

#### Args:

* <b>`tensors`</b>: The input tensors across which to sum; must be assigned
    to GPU devices.


#### Returns:

A tensor containing the sum of the input tensors.


#### Raises:

* <b>`LookupError`</b>: If context is not currently using a GPU device.