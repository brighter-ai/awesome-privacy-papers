# Awesome Privacy Papers for Visual Data [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Twitter Follow](https://img.shields.io/twitter/follow/brighterai.svg?style=social)](https://twitter.com/brighterai)

[<img src="logo.png" align="right" width="100">](https://brighter.ai)

The ongoing AI driven data analytics revolution requires an enormous amount of visual data. At the same time, it is a social responsibility to protect individuals privacy linked to these data.

We care deeply about privacy. To strengthen our knowledge in this field and understand how it relates to visual data, we do constant research in the latest scientific works about this topic.

We want to share with you a curated list of machine/deep learning papers that address the topic of privacy in visual data.


## Contents

- [2022](#2022)
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

## 2022
- [DeepPrivacy2: Towards Realistic Full-Body Anonymization](https://arxiv.org/abs/2211.09454) - H. Hukkelas, F. Lindseth - Authors show a anonymization framework (DeepPrivacy2) for realistic anonymization of human figures and faces. Is based on a style-based GAN that outputs high quality and editable anonymizations. A new dataset for human figure synthesis is introduced. [[code](https://github.com/hukkelas/deep_privacy2)]

## 2020
- [PE-MIU: A Training-Free Privacy-Enhancing Face Recognition Approach Based on Minimum Information Units](https://doi.org/10.1109/ACCESS.2020.2994960) - P. Terhörst, K. Riehl , N. Damer, P. Rot, B. Bortolato, F. Kirchbuchner, V. Struc, A. Kuijper - Authors improve on training-free privacy-preserving face recognition approach based on dividing a face template into several minimum information units (MIUs) blocks and randomly changing their position in the template. [[code](https://github.com/pterhoer/PrivacyPreservingFaceRecognition/blob/master/training_free/pe_miu/privacy_enhancing_miu.py)]
- [Unsupervised Enhancement of Soft-biometric Privacy with Negative Face Recognition](https://arxiv.org/abs/2002.09181) - P. Terhörst, M. Huber, N. Damer, F. Kirchbuchner, A. Kuijper - Authors propose unsupervised privacy-preserving face recognition approach based on representing face templates in a complementary (negative) domain that describes facial properties that does not exist for this individual. [[code](https://github.com/pterhoer/PrivacyPreservingFaceRecognition/blob/master/unsupervised/negative_face_recognition/negative_face_recognition.py)]
- [Fawkes: Protecting Personal Privacy against Unauthorized Deep Learning Models](https://arxiv.org/abs/2002.08327) - S. Shan, E. Wenger, J. Zhang, H. Li, H. Zheng, B. Y. Zhao – Authors propose Fawkes, system that adds small perturbation to images ('cloaks'), which impairs identification systems effectiveness and protects users privacy against unauthorized facial recognition models. [[code](https://github.com/Shawn-Shan/fawkes)]
- [PrivacyNet: Semi-Adversarial Networks for Multi-attribute Face Privacy](https://arxiv.org/abs/2001.00561) - V. Mirjalili, S. Raschka, A. Ross – PrivacyNet, using a GAN-based Semi-adversarial Network (SAN), modifies an input face image in way that only some selective attributes can be reliably classified by third-party biometric algorithms.
- [Adversarial Privacy-preserving Filter](https://arxiv.org/abs/2007.12861) - J. Zhang, J. Sang, X. Zhao, X. Huang, Y. Sun, Y. Hu – This work proposes an adversarial privacy-preserving filter (APF) that adds an adversarial noise perturbation (not visible for humans) to a face image in order to impair unauthorized face recognition models. The protocol is introduced in the context of photo sharing services, where the user uploads face images to this service and the privacy-preserving filter is added in the cloud before the image is being shared.

## 2019
- [Live Face De-Identification in Video](https://arxiv.org/abs/1911.08348) - O. Gafni, L. Wolf, Y. Taigman – With an adversarial autoencoder in its core, the authors introduce a network architecture that, given an input face image, is trained to output a new face image that maximally decorrelates the identity while preserving the image context of its input (pose, illumination and expression).
- [Password-conditioned Anonymization and Deanonymization with Face Identity Transformers](https://arxiv.org/abs/1911.11759) - X. Gu, W. Luo, M. S. Ryoo, Y. Jae Lee - Authors present a privacy-preserving face identity transformer with a password embedding scheme, multimodal identity change, and a multi-task learning objective. Given the right password, it has the ability to recover the original input, but will return a wrong face when presented with incorrect password.
- [AnonymousNet: Natural Face De-Identification with Measurable Privacy](https://arxiv.org/abs/1904.12620) - T. Li, L. Lin - Authors propose a 4-stage framework -  facial  feature  extraction,  semantic-based attribute obfuscation, de-identified face generation and adversarial perturbation - to gain the ability to generate photo-realistic images with fake identity, while balancing privacy and usability both qualitatively and quantitatively.
- [DeepPrivacy: A Generative Adversarial Network for Face Anonymization](https://arxiv.org/abs/1909.04538) - H. Hukkelås, R. Mester, F. Lindseth - Authors present a conceptually simple GAN architecture to anonymize faces without destroying the original data distribution. Interestingly enough, the network never sees the original face. [[code](https://github.com/hukkelas/DeepPrivacy)]
- [FlowSAN: Privacy-enhancing Semi-Adversarial Networks to Confound Arbitrary Face-based Gender Classifiers](https://arxiv.org/abs/1905.01388) - V. Mirjalili, S. Raschka, A. Ross - Authors propose a method that sequentially combines diverse perturbations for an input face image to confound the gender information with respect to an arbitrary gender classifier, while preserving the face identity.
- [Unsupervised privacy-enhancement of face representations using similarity-sensitive noise transformations](https://doi.org/10.1007/s10489-019-01432-5) - P. Terhörst, N. Damer, F. Kirchbuchner, A. Kuijper - Authors propose training-free privacy-preserving face recognition approach based on similarity-sensitive noise transformations and dimensionality reduction techniques for face templates. [[code](https://github.com/pterhoer/PrivacyPreservingFaceRecognition/blob/master/training_free/similiarity_sensitive_noise_transformation/similarity_sensitive_noise_transformation.py)]
- [FSGAN: Subject Agnostic Face Swapping and Reenactment](https://arxiv.org/abs/1908.05932) - Y. Nirkin, Y. Keller, T. Hassner - Authors present Face Swapping GAN (FSGAN) for face swapping and reenactment, which can be applied to pairs of faces without requiring training on those faces and works both with single image and video sequence. [[code](https://github.com/YuvalNirkin/fsgan)]

## 2018
- [Learning to Anonymize Faces for Privacy Preserving Action Detection](https://arxiv.org/abs/1803.11556) - Z. Ren, Y. Jae Lee, M. S. Ryoo - Authors present a novel approach to learn a face anonymizer and activity detector using an adversarial learning formulation. The end result is a video anonymizer that performs pixel-level modifications to anonymize each person’s face, with minimal effect on action detection performance.
- [On Hallucinating Context and Background Pixels from a Face Mask using Multi-scale GANs](https://arxiv.org/abs/1811.07104) - S. Banerjee, W. J. Scheirer, K. W. Bowyer, P. J. Flynn - Authors propose a multi-scale GAN model that can synthesize realistic context (forehead, hair, neck, clothes) and background pixels given a masked face input, without any user supervision. The generated face images can be used as stock images by the media without any privacy concerns.
- [Privacy-Protective-GAN for Face De-identification](https://arxiv.org/abs/1806.08906) - Y. Wu, F. Yang, H. Ling - Authors present a generative approach, which integrates de-identification metric into the objective function to ensure privacy protection, while it retains utility and visual similarity with a regulator.

## 2017
- [Privacy-Preserving Visual Learning Using Doubly Permuted Homomorphic Encryption](https://arxiv.org/abs/1704.02203) - R. Yonetani, V. N. Boddeti, K. M. Kitani, Y. Sato - Authors develop a privacy-preserving framework with a new encryption scheme called doubly-permuted homomorphic encryption (DPHE). This framework is designed to aggregate multiple visual classifiers updated locally using private data and to ensure that no private information about the data is exposed during and after its learning procedure. [[code](https://github.com/yonetaniryo/DPHE-demo)]
- [Adversarial Image Perturbation for Privacy Protection: A Game Theory Perspective](https://arxiv.org/abs/1703.09471) - S. Joon Oh, M. Fritz, B. Schiele - Authors construct a game theoretical framework to study a system with two players, user and recogniser, with antagonistic goals and examine existing and new adversarial image perturbation techniques for the user. [[code](https://github.com/coallaoh/AIP)]
- [Semi-Adversarial Networks: Convolutional Autoencoders for Imparting Privacy to Face Images](https://arxiv.org/abs/1712.00321) - V. Mirjalili, S. Raschka, A. Namboodiri, A. Ross - Authors design convolutional autoencoder that transforms an input face image such that the transformed image can be successfully used for face recognition but not for gender classification. The training is facilitated by attaching a semi-adversarial module consisting of an auxiliary gender classifier and an auxiliary face matcher to the autoencoder. [[code](https://github.com/iPRoBe-lab/semi-adversarial-networks)]
- [Soft Biometric Privacy: Retaining Biometric Utility of Face Images while Perturbing Gender](https://doi.org/10.1109/BTAS.2017.8272743) - V. Mirjalili, A. Ross - Authors propose a method that entails iteratively perturbing a given face image, such that the performance of the face matcher is not adversely affected, but that of the soft biometric classifier is confounded.

## 2016
- [Privacy-CNH: A Framework to Detect Photo Privacy with Convolutional Neural Network using Hierarchical Features](https://www.cs.rochester.edu/u/jliu/paper/privacy-AAAI-2016.pdf) - L. Tram, D. Kong, H. Jin, J. Liu - Authors propose a new framework called Privacy-CNH that utilizes hierarchical features which include both object and convolutional features in a deep learning model to detect privacy at risk photos. The generation of object features enables model to better inform the users about the reason why a photo has privacy risk.
- [Privacy-Preserving Human Activity Recognition from Extreme Low Resolution](https://arxiv.org/abs/1604.03196) - M. S. Ryoo, B. Rothrock, C. Fleming, H. J. Yang - Authors address human activity recognition while only using extreme low-resolution videos using an approach of *inverse super resolution*, with the intention of creating a computer vision system, that can recognize human activities and assist our daily life, yet ensure that it is not recording video, that may invade our privacy.
- [Faceless Person Recognition: Privacy Implications in Social Media](https://arxiv.org/abs/1607.08438) - S. J. Oh, R. Benenson, M. Fritz, B. Schiele - Authors raise concern of privacy implications by analysing how well people are recognisable in social media data in different scenarios.
- [De-identification for Privacy Protection in Multimedia Content: A Survey](https://doi.org/10.1016/j.image.2016.05.020) - S. Ribaric, A. Ariyaeeinia, N. Pavesic - In an extensive survey, authors present de-identification of various non-biometric as well as behavioural and physiological identifiers. They announce some new directions in the de-identification research and point out the problems of detecting and removing social and environmental privacy sensitive context.

## 2015
- [Towards privacy-preserving recognition of human activities](https://doi.org/10.1109/ICIP.2015.7351605) - J. Dai, B. Saghafi, J. Wu, J. Konrad, P. Ishwar - Authors studied and quantified the impact of camera resolution on action recognition accuracy in a simulated environment (Unity3D + Kinect v2). Results for a dataset of 12 individuals performing 4 actions indiate, somewhat surprisingly, that the recognition accuracy at single-pixel resolution can be quite close to that at 100 × 100 resolution, suggesting that reliable action recognition can be achieved without compromising occupant’s identity. [[project page](http://vip.bu.edu/projects/vsns/privacy-smartroom/)]
- [Attribute Preserved Face De-identification](https://doi.org/10.1109/ICB.2015.7139096) - A. Jourabloo, X. Yin, X. Liu - Authors propose an optimization-based method for face de-identification with the goal of changing the identity of a test image while preserving a large set of facial attributes. They combine the attribute classifiers and face verification classifier in a joint objective function.
- [The Privacy-Utility Tradeoff for Remotely Teleoperated Robots](https://doi.org/10.1145/2696454.2696484) - D. J. Butler, J. Huang, F. Rosener, M. Cakmak - Authors explore the privacy-utility tradeoff for remotely teleoperated robots in the home with two surveys that provide a framework for understanding the privacy attitudes of end-users, and with a user study that empirically examines the effect of different filters of visual information on the ability of a teleoperator to carry out a task.
- [An Overview of Face De-identification in Still Images and Videos](https://doi.org/10.1109/FG.2015.7285017) - S. Ribaric, N. Pavesic - Authors perform a survey of existing de-identification methods, outline the main issues and provide motivation for the research of such methods.
- [Controllable Face Privacy](https://doi.org/10.1109/FG.2015.7285018) - T. Sim, L. Zhang - Authors apply a subspace decomposition onto face encoding scheme, effectively decoupling facial attributes such as gender, age, and identity into mutually orthogonal subspaces, which in turn enables independent control of these attributes. This approach protects identity privacy, and yet allows other computer vision analyses, such as gender detection, to proceed unimpeded.

## 2014
- [Privacy of Facial Soft Biometrics: Suppressing Gender But Retaining Identity](https://doi.org/10.1007/978-3-319-16181-5_52) - A. Othman, A. Ross - Authors explore the possibility of mixing face images of opposite genders to suppress the gender classification, while bearing sufficient similarity in terms of a face matcher.

## 2009
- [Face De-Identification](https://doi.org/10.1007/978-1-84882-301-3_8) - R. Gross, L. Sweeney, J. Cohn, F. de la Torre, S. Baker - Authors introduce a novel de-identification framework using multi-factor models which unify linear, bilinear, and quadratic data models. They demonstrate that the algorithm protects privacy (as measured by face recognition performance) while preserving data utility (as measured by facial expression classification performance on de-identified images) and suggests that the new model extends directly to image sequences.

## 2006
- [Model-Based Face De-Identification](https://doi.org/10.1109/CVPRW.2006.125) - R. Gross, L. Sweeney, F. de la Torre, S. Baker - Authors improve on an algorithm for the protection of privacy in facial images, called *k*-Same-M algorithm, with focus on better image quality than its predecessors.
- [People Identification with Limited Labels in Privacy-Protected Video](https://doi.org/10.1109/ICME.2006.262703) - Y. Chang, R. Yan, D. Chen, J. Yang - Authors explore two-step labeling process for video data that balance the insufficient training data and the people privacy protection: one set of labeled data is provided by authorized personnel from original video and the other set of imperfect pairwise constraints is labeled by unauthorized personnel from original video with masked face. The effectiveness of the proposed approach is demonstrated using video captured from a nursing home environment.
- [Blur Filtration Fails to Preserve Privacy for Home-Based Video Conferencing](https://doi.org/10.1145/1143518.1143519) - C. Neustaedter, S. Greenberg, M. Boyle - Authors begin by reinterpreting the result of previous study (Boyle et al. 2000), stating that bluring the video does not balance privacy and awareness for risky situations, since people do not feel comfortable with relying on such techniques. Secondly, they outline a set of design implications that suggest strategies for balancing privacy and awareness.

## 2005
- [Preserving Privacy by De-identifying Facial Images](https://doi.org/10.1109/TKDE.2005.32) - E. Newton, L. Sweeney, B. Malin - This paper presents a new privacy-preserving algorithm for face recognition, named k-Same, that determines similarity between faces based on a distance metric and creates new faces by averaging image components, which may be the original image pixels (k-Same-Pixel) or eigenvectors (k-Same-Eigen). Authors also conduct research on related works and real-world privacy implications of their approach.
- [Integrating Utility into Face De-Identification](https://doi.org/10.1007/11767831_15) - R. Gross, E. Airoldi, B. Malin, L. Sweeney - Authors provide a comprehensive study on how various de-identification methods preserve face attributes / data utility and introduce a de-identification method, which was at the time superior to prior methods in both privacy protection and utility preservation.

## 2004
- [Blinkering Surveillance: Enabling Video Privacy through Computer Vision](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.68.4555) - A. W. Senior, S. Pankanti, A. Hampapur, L. M. Brown, Y. Tian, A. Ekin - Authors present a review of privacy topic in video surveillance and embody derived principles of privacy protection in a prototype system.
- [Robust Human Face Hiding Ensuring Privacy](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.72.4758) - I. Martinez-Ponte, X. Desurmont, J. Meessen, J-F. Delaigle - Authors present a face detection and tracking system with the intention of masking the face, thus making it unrecognizible. They do that by employing a lossy compression algorithm.

## 2003
- [Engineering Privacy in Public: Confounding Face Recognition](https://doi.org/10.1007/978-3-540-40956-4_7) - J. Alexander, J. M. Smith - The chief contribution of this paper is the empirical results of testing various face recognition countermeasures against the first of several systems - eigenfaces method, as well as a framework for interpreting those results.

## 2000
- [The Effects of Filtered Video on Awareness and Privacy](https://doi.org/10.1145/358916.358935) - M. Boyle, C. Edwards, S. Greenberg - Authors provide a study on how bluring and pixelation impacts privacy and attribute awareness in a video. They examine the following attributes - the number of actors, their posture, gender, busyness, seriousness, approachability and background objects.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
