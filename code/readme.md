# VoiceMixer: Adversarial Voice Style Mixup
### Anonymous Authors

This is repository for the official VoiceMixer.
[Demo page](https://anonymous-speech.github.io/voicemixer/index.html) for audio samples.

**Abstract :**
    Although recent advances in voice conversion have shown significant improvement, there still remains a gap between the converted voice and target voice. A key factor that maintains this gap is the insufficient decomposition of content and voice style from the source speech. This insufficiency leads to the converted speech containing source speech style or losing source speech content. In this paper, we present VoiceMixer which can effectively decompose and transfer voice style through a novel information bottleneck and adversarial feedback. With self-supervised representation learning, the proposed information bottleneck can decompose the content and style with only a small loss of content information. Also, for adversarial feedback of each information, the discriminator is decomposed into content and style discriminator with self-supervision, which enable our model to achieve better generalization to the voice style of the converted speech. The experimental results show the superiority of our model in disentanglement and transfer performance, and improve audio quality by preserving content information.

## Neurips2021 Policy
To minimize the potential harms, malicious use, and ethical concerns of voice conversion technology, 
the Neurips committee recommended the restricted release of model. 
Hence, we will provide the source code only through restricted access. 
Please request the source code by submitting this request form [[link]](). 
Please read the terms of agreement carefully and fill in the form to use the source code. 
You must agree to the terms. You may not use the source code if you do not accept the terms.

Most of the terms are about the agreement not to use to deceive people.


## References
* We thank the author of [HiFi-GAN](https://github.com/jik876/hifi-gan) for their great repository and paper.

