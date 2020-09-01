# Awesome Privacy Papers for Visual Data [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Twitter Follow](https://img.shields.io/twitter/follow/brighterai.svg?style=social)](https://twitter.com/brighterai)

[<img src="logo.png" align="right" width="100">](https://brighter.ai)

The ongoing AI driven data analytics revolution requires an enormous amount of visual data. At the same time, it is a social responsibility to protect individuals privacy linked to these data.

We care deeply about privacy. To strengthen our knowledge in this field and understand how it relates to visual data, we do constant research in the latest scientific works about this topic.

We want to share with you a curated list of machine/deep learning papers that address the topic of privacy in visual data.


## Contents

- [2020](#2020)
- [2019](#2019)
- [2018](#2018)
- [2017](#2017)
- [2016](#2016)
- [2015](#2015)
- [2014](#2014)
- [2009](#2009)
- [2006](#2006)
- [2005](#2005)
- [2004](#2004)
- [2003](#2003)
- [2000](#2000)


## 2020
- [PE-MIU: A Training-Free Privacy-Enhancing Face Recognition Approach Based on Minimum Information Units](https://doi.org/10.1109/ACCESS.2020.2994960) - P. Terhörst, K. Riehl , N. Damer, P. Rot, B. Bortolato, F. Kirchbuchner, V. Struc, A. Kuijper - Authors improve on training-free privacy-preserving face recognition approach based on dividing a face template into several minimum information units (MIUs) blocks and randomly changing their position in the template ([code](https://github.com/pterhoer/PrivacyPreservingFaceRecognition/blob/master/training_free/pe_miu/privacy_enhancing_miu.py)).
- [Unsupervised Enhancement of Soft-biometric Privacy with Negative Face Recognition](https://arxiv.org/abs/2002.09181) - P. Terhörst, M. Huber, N. Damer, F. Kirchbuchner, A. Kuijper - Authors propose unsupervised privacy-preserving face recognition approach based on representing face templates in a complementary (negative) domain that describes facial properties that does not exist for this individual ([code](https://github.com/pterhoer/PrivacyPreservingFaceRecognition/blob/master/unsupervised/negative_face_recognition/negative_face_recognition.py)).
- [Fawkes: Protecting Personal Privacy against Unauthorized Deep Learning Models](https://arxiv.org/abs/2002.08327) - S. Shan, E. Wenger, J. Zhang, H. Li, H. Zheng, B. Y. Zhao – Authors propose Fawkes, system that adds small perturbation to images ('cloaks'), which impairs identification systems effectiveness and protects users privacy against unauthorized facial recognition models ([code](https://github.com/Shawn-Shan/fawkes)).
- [PrivacyNet: Semi-Adversarial Networks for Multi-attribute Face Privacy](https://arxiv.org/abs/2001.00561) - V. Mirjalili, S. Raschka, A. Ross – PrivacyNet, using a GAN-based Semi-adversarial Network (SAN), modifies an input face image in way that only some selective attributes can be reliably classified by third-party biometric algorithms.
- [Adversarial Privacy-preserving Filter](https://arxiv.org/abs/2007.12861) - J. Zhang, J. Sang, X. Zhao, X. Huang, Y. Sun, Y. Hu – This work proposes an adversarial privacy-preserving filter (APF) that adds an adversarial noise perturbation (not visible for humans) to a face image in order to impair unauthorized face recognition models. The protocol is introduced in the context of photo sharing services, where the user uploads face images to this service and the privacy-preserving filter is added in the cloud before the image is being shared.

## 2019
- [Live Face De-Identification in Video](https://arxiv.org/abs/1911.08348) - O. Gafni, L. Wolf, Y. Taigman – With an adversarial autoencoder in its core, the authors introduce a network architecture that, given an input face image, is trained to output a new face image that maximally decorrelates the identity while preserving the image context of its input (pose, illumination and expression).
- [Password-conditioned Anonymization and Deanonymization with Face Identity Transformers](https://arxiv.org/abs/1911.11759) - X. Gu, W. Luo, M. S. Ryoo, Y. Jae Lee - Authors present a privacy-preserving face identity transformer with a password embedding scheme, multimodal identity change, and a multi-task learning objective. Given the right password, it has the ability to recover the original input, but will return a wrong face when presented with incorrect password.
- [AnonymousNet: Natural Face De-Identification with Measurable Privacy](https://arxiv.org/abs/1904.12620) - T. Li, L. Lin - Authors propose a 4-stage framework -  facial  feature  extraction,  semantic-based attribute obfuscation, de-identified face generation and adversarial perturbation - to gain the ability to generate photo-realistic images with fake identity, while balancing privacy and usability both qualitatively and quantitatively.
- [DeepPrivacy: A Generative Adversarial Network for Face Anonymization](https://arxiv.org/abs/1909.04538) - H. Hukkelås, R. Mester, F. Lindseth - Authors present a conceptually simple GAN architecture to anonymize faces without destroying the original data distribution. Interestingly enough, the network never sees the original face ([code](https://github.com/hukkelas/DeepPrivacy)).
- [FlowSAN: Privacy-enhancing Semi-Adversarial Networks to Confound Arbitrary Face-based Gender Classifiers](https://arxiv.org/abs/1905.01388) - V. Mirjalili, S. Raschka, A. Ross - Authors propose a method that sequentially combines diverse perturbations for an input face image to confound the gender information with respect to an arbitrary gender classifier, while preserving the face identity.
- [Unsupervised privacy-enhancement of face representations using similarity-sensitive noise transformations](https://doi.org/10.1007/s10489-019-01432-5) - P. Terhörst, N. Damer, F. Kirchbuchner, A. Kuijper - Authors propose training-free privacy-preserving face recognition approach based on similarity-sensitive noise transformations and dimensionality reduction techniques for face templates ([code](https://github.com/pterhoer/PrivacyPreservingFaceRecognition/blob/master/training_free/similiarity_sensitive_noise_transformation/similarity_sensitive_noise_transformation.py)).
- [FSGAN: Subject Agnostic Face Swapping and Reenactment](https://arxiv.org/abs/1908.05932) - Y. Nirkin, Y. Keller, T. Hassner - Authors present Face Swapping GAN (FSGAN) for face swapping and reenactment, which can be applied to pairs of faces without requiring training on those faces and works both with single image and video sequence ([code](https://github.com/YuvalNirkin/fsgan)).

## 2018
- [Learning to Anonymize Faces for Privacy Preserving Action Detection](https://arxiv.org/abs/1803.11556) - Z. Ren, Y. Jae Lee, M. S. Ryoo.
- [On Hallucinating Context and Background Pixels from a Face Mask using Multi-scale GANs](https://arxiv.org/abs/1811.07104) - S. Banerjee, W. J. Scheirer, K. W. Bowyer, P. J. Flynn.
- [Privacy-Protective-GAN for Face De-identification](https://arxiv.org/abs/1806.08906) - Y. Wu, F. Yang, H. Ling.

## 2017
- [Privacy-Preserving Visual Learning Using Doubly Permuted Homomorphic Encryption](https://arxiv.org/abs/1704.02203) - R. Yonetani, V. N. Boddeti, K. M. Kitani, Y. Sato.
- [Adversarial Image Perturbation for Privacy Protection: A Game Theory Perspective](https://arxiv.org/abs/1703.09471) - S. Joon Oh, M. Fritz, B. Schiele.
- [Semi-Adversarial Networks: Convolutional Autoencoders for Imparting Privacy to Face Images](https://arxiv.org/abs/1712.00321) - V. Mirjalili, S. Raschka, A. Namboodiri, A. Ross.
- [Soft Biometric Privacy: Retaining Biometric Utility of Face Images while Perturbing Gender](https://doi.org/10.1109/BTAS.2017.8272743) - V. Mirjalili, A. Ross.

## 2016
- [Privacy-CNH: A Framework to Detect Photo Privacy with Convolutional Neural Network using Hierarchical Features](https://www.cs.rochester.edu/u/jliu/paper/privacy-AAAI-2016.pdf) - L. Tram, D. Kong, H. Jin, J. Liu.
- [Privacy-Preserving Human Activity Recognition from Extreme Low Resolution](https://arxiv.org/abs/1604.03196) - M. S. Ryoo, B. Rothrock, C. Fleming, H. J. Yang.
- [Faceless Person Recognition: Privacy Implications in Social Media](https://arxiv.org/abs/1607.08438) - S. J. Oh, R. Benenson, M. Fritz, B. Schiele.
- [De-identification for Privacy Protection in Multimedia Content: A Survey](https://doi.org/10.1016/j.image.2016.05.020) - S. Ribaric, A. Ariyaeeinia, N. Pavesic.

## 2015
- [Towards privacy-preserving recognition of human activities](https://doi.org/10.1109/ICIP.2015.7351605) - J. Dai, B. Saghafi, J. Wu, J. Konrad, P. Ishwar.
- [Attribute Preserved Face De-identification](https://doi.org/10.1109/ICB.2015.7139096) - A. Jourabloo, X. Yin, X. Liu.
- [The Privacy-Utility Tradeoff for Remotely Teleoperated Robots](https://doi.org/10.1145/2696454.2696484) - D. J. Butler, J. Huang, F. Rosener, M. Cakmak.
- [An Overview of Face De-identification in Still Images and Videos](https://doi.org/10.1109/FG.2015.7285017) - S. Ribaric, N. Pavesic - Authors perform a survey of existing de-identification methods, outline the main issues and provide motivation for the research of such methods.
- [Controllable Face Privacy](https://doi.org/10.1109/FG.2015.7285018) - T. Sim, L. Zhang.

## 2014
- [Privacy of Facial Soft Biometrics: Suppressing Gender But Retaining Identity](https://doi.org/10.1007/978-3-319-16181-5_52) - A. Othman, A. Ross - Authors explore the possibility of mixing face images of opposite genders to suppress the gender classification, while bearing sufficient similarity in terms of a face matcher.

## 2009
- [Face De-Identification](https://doi.org/10.1007/978-1-84882-301-3_8) - R. Gross, L. Sweeney, J. Cohn, F. de la Torre, S. Baker.

## 2006
- [Model-Based Face De-Identification](https://doi.org/10.1109/CVPRW.2006.125) - R. Gross, L. Sweeney, F. de la Torre, S. Baker - Authors introduce an algorithm for the protection of privacy in facial images, called *k*-Same-M algorithm, with focus on better image quality than its predecessors.

- [People Identification with Limited Labels in Privacy-Protected Video](https://doi.org/10.1109/ICME.2006.262703) - Y. Chang, R. Yan, D. Chen, J. Yang.
- [Blur Filtration Fails to Preserve Privacy for Home-Based Video Conferencing](https://doi.org/10.1145/1143518.1143519) - C. Neustaedter, S. Greenberg, M. Boyle - Authors begin by reinterpreting the result of previous study (Boyle et al. 2000), stating that bluring the video does not balance privacy and awareness for risky situations, since people do not feel comfortable with relying on such techniques. Secondly, they outline a set of design implications that suggest strategies for balancing privacy and awareness.

## 2005
- [Preserving Privacy by De-identifying Facial Images](https://doi.org/10.1109/TKDE.2005.32) - E. Newton, L. Sweeney, B. Malin.
- [Integrating Utility into Face De-Identification](https://doi.org/10.1007/11767831_15) - R. Gross, E. Airoldi, B. Malin, L. Sweeney - Authors provide a comprehensive study on how various de-identification methods preserve face attributes / data utility and introduce a de-identification method, which was at the time superior to prior methods in both privacy protection and utility preservation.

## 2004
- [Blinkering Surveillance: Enabling Video Privacy through Computer Vision](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.68.4555) - A. W. Senior, S. Pankanti, A. Hampapur, L. M. Brown, Y. Tian, A. Ekin.
- [Robust Human Face Hiding Ensuring Privacy](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.72.4758) - I. Martinez-Ponte, X. Desurmont, J. Meessen, J-F. Delaigle - Authors present a face detection and tracking system with the intention of masking the face, thus making it unrecognizible. They do that by employing a lossy compression algorithm.

## 2003
- [Engineering Privacy in Public: Confounding Face Recognition](https://doi.org/10.1007/978-3-540-40956-4_7) - J. Alexander, J. M. Smith.

## 2000
- [The Effects of Filtered Video on Awareness and Privacy](https://doi.org/10.1145/358916.358935) - M. Boyle, C. Edwards, S. Greenberg - Authors provide a study on how bluring and pixelation impacts privacy and attribute awareness in a video. They examine the following attributes - the number of actors, their posture, gender, busyness, seriousness, approachability and background objects.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
