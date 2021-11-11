# VGAT
 PyG realisation of Variatianl AutoEncoder, based on [Variational Graph Auto-Encoders](http://arxiv.org/abs/1611.07308)。

I use Cora as my dataset, and achieves nearly 89.0 to 91.0 for both AUC and AP. It's a little lower than the score in paper (91.4 and 92.6 for AUC and AP respectively), but I haven't fine-tuned the hyper-parameter. 

Thanks to PyG, I'm able to reproduce the VGAT with little work, and since the code is easy to understand.
