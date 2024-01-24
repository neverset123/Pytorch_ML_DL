## machine learning
1) statistics: better understand the mechanism to create data (over simplification)
2) machine learning: recognize pattern, able to create extremely flexible and complex models

## hyperparameter
### batch size
Batch size is related to the quantity of data fed to your GPU. a high batch size will result in a better estimation of the gradient when your optimizer updates the weights.

```
Max_batch_size= available_GPU_memory_bytes / 4 / (size_of_tensors + trainable_parameters)
```




