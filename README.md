### 인공지능과 공감능력: Artificial Intelligence and Empathy

* 인간의 공감 능력을 뇌인지과학적, 심리학적으로 이해하고 이를 인공지능 시스템에 통합하는 방안을 탐구한다.
* 감성컴퓨팅, BERT 및 Transformer와 같은 딥러닝 기반 자연어 처리 기술을 활용해 감정 인식과 공감 반응 생성 메커니즘을 분석한다.
* 인간-기계 상호작용의 윤리적 쟁점을 함께 고찰함으로써, 인간 친화적인 AI 설계의 이론적·기술적 기반을 구축 한다.


#### 감성컴퓨팅

* Picard, R. W. (1995). Affective computing (Technical Report No. 321). MIT Media Laboratory, Perceptual Computing Section.
    * [Original Paper Link](https://affect.media.mit.edu/pdfs/95.picard.pdf)

* Wang, Y., Song, W., Tao, W., Liotta, A., Yang, D., Li, X., Gao, S., Sun, Y., Ge, W., Zhang, W., & Zhang, W. (2022). A systematic review on affective computing: Emotion models, databases, and recent advances. Information Fusion, 83–84, 19–52. https://doi.org/10.1016/j.inffus.2022.03.009
    * [Original Paper Link](https://arxiv.org/abs/2203.06935).

* Picard, R. W. (2003). Affective computing: Challenges. International Journal of Human-Computer Studies, 59(1–2), 55–64. https://doi.org/10.1016/S1071-5819(03)00052-1
    * [Original Paper Link](https://doi.org/10.1016/S1071-5819(03)00052-1).
)



#### Natural Language Processing (자연어 처리)

* Single Headed Attention RNN: Stop Thinking With Your Head (2020)
    * [Original Paper Link](https://arxiv.org/abs/1911.11423) / Paper Review Video / Summary PDF / Code Practice
* BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding (NAACL 2019)
    * [Original Paper Link](https://arxiv.org/abs/1810.04805) / Paper Review Video / Summary PDF / Code Practice
* Attention is All You Need (NIPS 2017)
    * [Original Paper Link](https://arxiv.org/abs/1706.03762) / [Paper Review Video](https://www.youtube.com/watch?v=AA621UofTUA) / [Summary PDF](/lecture_notes/Transformer.pdf) / [Code Practice](/code_practices/Attention_is_All_You_Need_Tutorial_(German_English).ipynb)
* Neural Machine Translation by Jointly Learning to Align and Translate (ICLR 2015 Oral)
    * [Original Paper Link](https://arxiv.org/abs/1409.0473) / Paper Review Video / Summary PDF / [Code Practice](/code_practices/Sequence_to_Sequence_with_Attention_Tutorial.ipynb)
* Show and Tell: A Neural Image Caption Generator (CVPR 2015)
    * [Original Paper Link](https://arxiv.org/abs/1411.4555) / Paper Review Video / Summary PDF / [Code Practice](/code_practices/Neural_Image_Captioning_(NIC)_Using_ResNet_101.ipynb)
* Sequence to Sequence Learning with Neural Networks (NIPS 2014)
    * [Original Paper Link](https://arxiv.org/abs/1409.3215) / [Paper Review Video](https://www.youtube.com/watch?v=4DzKM0vgG1Y) / [Summary PDF](/lecture_notes/Seq2Seq.pdf) / [Code Practice](/code_practices/Sequence_to_Sequence_with_LSTM_Tutorial.ipynb)

#### Generative Model & Super Resolution (생성 모델 & 해상도 복원)

* Meta-Transfer Learning for Zero-Shot Super-Resolution (CVPR 2020)
    * [Original Paper Link](https://arxiv.org/abs/2002.12213) / [Paper Review Video](https://www.youtube.com/watch?v=PUtFz4vqXHQ) / [Summary PDF](/lecture_notes/MZSR.pdf) / Code Practice
* SinGAN: Learning a Generative Model from a Single Natural Image (ICCV 2019)
    * [Original Paper Link](https://arxiv.org/abs/1905.01164) / Paper Review Video / Summary PDF / Code Practice
* A Style-Based Generator Architecture for Generative Adversarial Networks (CVPR 2019)
    * [Original Paper Link](https://arxiv.org/abs/1812.04948) / Paper Review Video / [Summary PDF](/lecture_notes/StyleGAN.pdf) / Code Practice
* StarGAN: Unified Generative Adversarial Networks for Multi-Domain Image-to-Image Translation (CVPR 2018 Oral)
    * [Original Paper Link](https://arxiv.org/abs/1711.09020) / [Paper Review Video](https://www.youtube.com/watch?v=-r9M4Cj9o_8) / [Summary PDF](/lecture_notes/StarGAN.pdf) / [Code Practice](/code_practices/StarGAN_Tutorial.ipynb)
* Image-to-Image Translation with Conditional Adversarial Networks (CVPR 2017)
    * [Original Paper Link](https://arxiv.org/abs/1611.07004) / [Paper Review Video](https://www.youtube.com/watch?v=ImiD4npRj7k) / [Summary PDF](/lecture_notes/Pix2Pix.pdf) / [Code Practice](/code_practices/Pix2Pix_for_Facades.ipynb)
* Generative Adversarial Nets (NIPS 2014)
    * [Original Paper Link](https://arxiv.org/abs/1406.2661) / [Paper Review Video](https://www.youtube.com/watch?v=AVvlDmhHgC4) / [Summary PDF](/lecture_notes/GAN.pdf) / [Code Practice](/code_practices/GAN_for_MNIST_Tutorial.ipynb)

#### Modeling & Optimization (모델링 & 최적화)

* Bag of Tricks for Image Classification (CVPR 2019)
    * [Original Paper Link](https://arxiv.org/abs/1812.01187) / Paper Review Video / [Summary PDF](/lecture_notes/Bag_of_Tricks_for_Image_Classification.pdf)
    * [CIFAR-10](/code_practices/ResNet18_CIFAR10_Basic_Training.ipynb) / [CIFAR-10 with Label Smoothing](/code_practices/ResNet18_CIFAR10_Training_with_Label_Smoothing.ipynb) / [CIFAR-10 with Input Mixup](/code_practices/ResNet18_CIFAR10_Training_with_Input_Mixup.ipynb) / [CIFAR-10 with Label Smoothing and Input Mixup](/code_practices/ResNet18_CIFAR10_Training_with_Input_Mixup_and_Label_Smoothing.ipynb)
* Deep Compression: Compressing Deep Neural Networks with Pruning, Trained Quantization and Huffman Coding (ICLR 2016 Oral)
    * [Original Paper Link](https://arxiv.org/abs/1510.00149) / Paper Review Video / Summary PDF / Code Practice
* Batch normalization: Accelerating deep network training by reducing internal covariate shift (PMLR 2015)
    * [Original Paper Link](https://arxiv.org/abs/1502.03167) / [Paper Review Video](https://www.youtube.com/watch?v=58fuWVu5DVU) / [Summary PDF](/lecture_notes/Batch_Normalization.pdf) / [Code Practice](/code_practices/Batch_Normalization_Evaluation_(with_Residual_Connection).ipynb)

#### Adversarial Examples & Backdoor Attacks (적대적 예제 & 백도어 공격)

* HopSkipJumpAttack: A Query-Efficient Decision-Based Attack (S&P 2020)
    * [Original Paper Link](https://arxiv.org/abs/1904.02144) / Paper Review Video/ Summary PDF / [Targeted Attack](/code_practices/Targeted_HopSkipJumpAttack_Using_CIFAR10.ipynb) / [Untargeted Attack](/code_practices/Untargeted_HopSkipJumpAttack_Using_CIFAR10.ipynb)
* Breaking certified defenses: Semantic adversarial examples with spoofed robustness certificates (ICLR 2020)
    * [Original Paper Link](https://arxiv.org/abs/2003.08937) / [Paper Review Video](https://www.youtube.com/watch?v=D1j3QiXPRag) / [Summary PDF](/lecture_notes/Shadow_Attack.pdf) / [Code Practice](/code_practices/Shadow_Attack_Tutorial.ipynb)
* Sign-OPT: A Query-Efficient Hard-label Adversarial Attack (ICLR 2020)
    * [Original Paper Link](https://arxiv.org/abs/1909.10773) / Paper Review Video / Summary PDF / [MNIST](/code_practices/Sign_OPT_Attack_for_MNIST.ipynb) / [CIFAR-10](/code_practices/Sign_OPT_Attack_for_CIFAR_10.ipynb)
* Is BERT Really Robust? A Strong Baseline for Natural Language Attack on Text Classification and Entailment (AAAI 2020 Oral)
    * [Original Paper Link](https://arxiv.org/abs/1907.11932) / [Paper Review Video](https://www.youtube.com/watch?v=EF-IYFTKZiE) / [Summary PDF](/lecture_notes/TextFooler.pdf) / [Code Practice](/code_practices/TextFooler_Tutorial.ipynb)
* Query-Efficient Hard-label Black-box Attack: An Optimization-based Approach (ICLR 2019)
    * [Original Paper Link](https://arxiv.org/abs/1807.04457) / Paper Review Video / [Summary PDF](/lecture_notes/OPT_Attack.pdf) / [MNIST](/code_practices/Opt_Attack_for_MNIST.ipynb) / [CIFAR-10](/code_practices/Opt_Attack_for_CIFAR_10.ipynb)
* Boosting Adversarial Attacks with Momentum (CVPR 2018 Spotlight)
    * [Original Paper Link](https://arxiv.org/abs/1710.06081) / Paper Review Video / [Summary PDF](/lecture_notes/Boosting_Adversarial_Attacks_with_Momentum.pdf) / [CIFAR-10](/code_practices/MI_FGSM_Attack_for_CIFAR_10.ipynb) / [ImageNet](/code_practices/MI_FGSM_Attack_for_ImageNet.ipynb)
* Poison Frogs! Targeted Clean-Label Poisoning Attacks on Neural Networks (NIPS 2018)
    * [Original Paper Link](https://arxiv.org/abs/1804.00792) / Paper Review Video / [Summary PDF](/lecture_notes/Poison_Frogs.pdf) / [ResNet](/code_practices/One_Shot_Kill_Poison_Attack_ResNet.ipynb) / [AlexNet](/code_practices/One_Shot_Kill_Poison_Attack_AlexNet.ipynb)
* Decision-Based Adversarial Attacks: Reliable Attacks Against Black-Box Machine Learning Models (ICLR 2018)
    * [Original Paper Link](https://arxiv.org/abs/1712.04248) / [Paper Review Video](https://www.youtube.com/watch?v=3dX_SsO2mis) / [Summary PDF](/lecture_notes/Boundary_Attack.pdf) / Code Practice

### 지난 논문 리뷰 콘텐츠

* Explaining and Harnessing Adversarial Examples (ICLR 2015)
    * [Original Paper Link](https://arxiv.org/abs/1412.6572) / [Paper Review Video](https://www.youtube.com/watch?v=99uxhAjNwps)
* Towards Evaluating the Robustness of Neural Networks (S&P 2017)
    * [Original Paper Link](https://arxiv.org/abs/1608.04644) / [Paper Review Video](https://www.youtube.com/watch?v=9kRWHKPyfwQ)
* Towards Deep Learning Models Resistant to Adversarial Attacks (ICLR 2018)
    * [Original Paper Link](https://arxiv.org/abs/1706.06083) / [Paper Review Video](https://www.youtube.com/watch?v=6RBpdAC9nwY)
* Adversarial Examples Are Not Bugs, They Are Features (NIPS 2019)
    * [Original Paper Link](https://arxiv.org/abs/1905.02175) / [Paper Review Video](https://www.youtube.com/watch?v=Y7O47Kq8pmU)
* Certified Robustness to Adversarial Examples with Differential Privacy (S&P 2019)
    * [Original Paper Link](https://arxiv.org/abs/1802.03471) / [Paper Review Video](https://www.youtube.com/watch?v=ySJUlEVlXfk)
* Obfuscated Gradients Give a False Sense of Security (ICML 2018)
    * [Original Paper Link](https://arxiv.org/abs/1802.00420) / [Paper Review Video](https://www.youtube.com/watch?v=0O_Bxln9bTw)
* Constructing Unrestricted Adversarial Examples with Generative Models (NIPS 2018)
    * [Original Paper Link](https://arxiv.org/abs/1805.07894) / [Paper Review Video](https://www.youtube.com/watch?v=IDtaVjJoV4g)
* Adversarial Patch (NIPS 2018)
    * [Original Paper Link](https://arxiv.org/abs/1712.09665) / [Paper Review Video](https://www.youtube.com/watch?v=pOlPlTCfCQE)
