# A lightweight perceptron of interlaced dense-sparse spatial patterns for image classification
**Abstract:**
Addressing dilated features has improved the learning ability of lightweight CNNbased networks in image representation. However, the performance is still at a
modest level due to a lack of global scattered features surrounding a local convolution region for their learning process. Meantime, taking into account multiple
large-kernel convolutions for these global features seems not to be suitable for a lightweight model due to the sharp increase in complexity. To deal with these
issues, a lightweight model is proposed by addressing three efficient concepts as follows. First, for an input tensor $\mathcal{T}$, a novel operator is proposed to extract its interlacing patterns in consideration of a robust spatial condensation of densesparse (DenSpa) information captured by convolving a dense kernel along withvarious sparse kernels surrounding a pixel region. Then, a DenSpa-based perceptron is introduced to effectively exploit the interlaced patterns of $\mathcal{T}$ for a learning process. Finally, a shallow backbone (named DenSpaNet) is constructed from a sequential process of DenSpa blocks for image representation. Experimental results on various benchmark datasets for image recognition have validated the efficiency of our proposals versus other lightweight models. 

<u>**A sample for training and validating DenSpaNet on ReIN<sup>100</sup>:**</u>

```
$ python DenSpaNet_ReIN.py #for training
$ python DenSpaNet_ReIN.py --evaluate #for validating
```
**Related citation(s):**

If you use any materials, please cite the following relevant work(s).

```
@article{DenSpaNetNguyen26,
  author       = {Thanh Tuan Nguyen, Ket Dong Vu, Hoang Anh Pham, Thinh Vinh Le, Hoai Nam Vu, Thanh Phuong Nguyen},
  title        = {A lightweight perceptron of interlaced dense-sparse spatial patterns for image classification},
  journal      = {Submitted to Pattern Analysis and Applications},
  volume       = {}
  page         = {}
  year         = {2026}
}
```


