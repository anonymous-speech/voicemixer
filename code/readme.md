# VoiceMixer: Adversarial Voice Style Mixup
### Anonymous Authors

This is repository for the official VoiceMixer.

[[Demo page]](https://anonymous-speech.github.io/voicemixer/index.html) for audio samples.

**Abstract :**
    Although recent advances in voice conversion have shown significant improvement, there still remains a gap between the converted voice and target voice. A key factor that maintains this gap is the insufficient decomposition of content and voice style from the source speech. This insufficiency leads to the converted speech containing source speech style or losing source speech content. In this paper, we present VoiceMixer which can effectively decompose and transfer voice style through a novel information bottleneck and adversarial feedback. With self-supervised representation learning, the proposed information bottleneck can decompose the content and style with only a small loss of content information. Also, for adversarial feedback of each information, the discriminator is decomposed into content and style discriminator with self-supervision, which enable our model to achieve better generalization to the voice style of the converted speech. The experimental results show the superiority of our model in disentanglement and transfer performance, and improve audio quality by preserving content information.

## Restricted Release
To minimize the potential harms, malicious use, and ethical concerns of voice conversion technology, 
the Neurips committee recommended the restricted release of model. 
Hence, we will provide the source code only through restricted access. 
Please request the source code by submitting this request form [[link]](https://docs.google.com/forms/d/e/1FAIpQLSclucpFYwApJ08guviKlLo9a9pFZk5nwmTQwIk5mrCvIgQI7g/viewform?usp=sf_link). 
Please read the terms of agreement carefully and fill in the form to use the source code. 
You must agree to the terms. You may not use the source code if you do not accept the terms.

Most of the terms are about the agreement not to use to deceive people.

## Terms and Conditions
Please read these Terms and Conditions carefully before using the source code of VoiceMixer. 
Your access to and use of the source code is conditioned on your acceptance of and compliance with these Terms. These Terms apply to all users who gains access to the source code. By selecting “Agree”, you are agreeing not to use the source code for: 
1.	Voice conversion of two parties (source and target speech) without written consent (excluding open-sourced, licensed datasets);
2.	Potential harmful and malicious conduct such as voice spoofing, phishing, and faking;
3.	Harassment of any kind using VoiceMixer;  
  
We acknowledge the potential risks that can be caused from inappropriate use of this source code. Therefore, we will strictly monitor the users requesting access to the source code and will only allow access if “Code Usage” statement is appropriate. 


## References
* We thank the author of [HiFi-GAN](https://github.com/jik876/hifi-gan) for their great repository and paper.
* We refered the [Again-VC](https://github.com/KimythAnly/AGAIN-VC) for instance normalization.
* We refered the [NPC](https://github.com/Alexander-H-Liu/NPC) for non-autoregressive contrastive learning.
