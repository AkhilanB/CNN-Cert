About CNN-Cert
=====================================
CNN-Cert is a general and efficient framework for certifying the robustness of convolutional neural networks (CNN). 
* CNN-Cert is **general**: it is able to certify lower bounds on the minimum adversarial distortion for a variety of CNNs with general activations (ReLU, tanh, sigmoid, arctan, etc), including those with convolutional layers, pooling layers, residual layers and batch-norm layers. In addition, it is a generalized version of previous robustness certification algorithms [Fast-Lin](https://arxiv.org/pdf/1804.09699.pdf) and [CROWN](https://arxiv.org/pdf/1811.00866.pdf) which focus on pure fully-connected networks with ReLU and general activations.   

* CNN-Cert is also **efficient**: it exploits convolutional structure to produce bounds more efficiently than comparable certification methods. We observed in our experiments that CNN-Cert achieves up to 17 and 11 times of speed-up compared to Fast-Lin and CROWN, and up to 366 times of speed-up compared to the dual-LP-based verification methods (see Tables 3-13 in our paper) while CNN-Cert obtains similar or even better robsutness certificates (a.k.a. certified lower bounds).

Cite our work:

Akhilan Boopathy, Tsui-Wei Weng, Pin-Yu Chen, Sijia Liu and Luca Daniel, "[**CNN-Cert: An Efficient Framework for Certifying Robustness of Convolutional
Neural Networks**](https://arxiv.org/pdf/1811.12395.pdf)", AAAI 2019.

```
@inproceedings{Boopathy2019cnncert,
  author = "Akhilan Boopathy AND Tsui-Wei Weng AND Pin-Yu Chen AND Sijia Liu AND Luca Daniel",
  title = "CNN-Cert: An Efficient Framework for Certifying Robustness of Convolutional
Neural Networks",
  booktitle = "AAAI",
  year = "2019",
  month = "Jan"
}
```

Code
-------------------------------------
Our codes will be released soon in December! Please stay tuned.
