## Workshop on Machine Learning for Audio Synthesis at ICML 2022

### About 
Audio synthesis plays a significant and fundamental role in many audio-based machine learning systems.  For example, text-to-speech models play an integral role in many widely-used smart speakers and other voice-based interaction systems. Outside of the speech domain, audio synthesis is used in the increasingly-popular domain of music generation, which shares connections to the emerging field of creativity in AI; such methods help to augment the composing process or enable more cost-efficient content generation.  Audio generation is also used as a general technique in self-supervised learning and audio data augmentation.


Much of development of the traditional techniques of data generation---such as generative adversarial networks, variational auto-encoders, diffusion models, and autoregressive models---have largely been carried out in fields outside of the audio domain, most notably in the computer vision domain.  While there certainly are a number of techniques developed specifically toward audio generation (e.g., WaveNet, Jukebox, Tacotron, among others), we believe that a machine learning workshop focused around generation in the audio domain would provide a good opportunity to bring together both practitioners of audio generation tools along with core machine learning researchers interested in audio, in order to hopefully forge new directions in this important area of research.


The 1st Machine Learning for Audio Synthesis workshop at ICML will attempt to cover the space of novel methods and applications of audio generation via machine learning. These include, but are not limited to: methods of speech modeling, environmental sound generation or other forms of ambient sound, novel generative models, music generation in the form of raw audio, and text-to-speech methods.  As part of the workshop, we plan to solicit original workshop papers in these areas, which will be reviewed by the committee and an additional set of reviewers.  

### Schedule
9:00   - **Invited Speaker Gus Xia** 

9:30   - **Invited Speaker Chris Donahue**

10:00 - **Contributed Talk - DrumGAN VST: A Plugin for Drum Sound Analysis/Synthesis with Autoencoding Generative Adversarial Networks**

10:20 - **Contributed Talk - Generating Detailed Music Datasets with Neural Audio Synthesis**

10:40 - **Contributed Talk - Adversarial Audio Synthesis with Complex-valued Polynomial Networks**

11:00 - **Morning Break**

11:30 - **Invited Speaker Mirco Ravanelli**

12:00 - **Lunch**

13:30 - **Poster & Demo Session**: Poster session alongside live demos from selected submissions.

15:00 - **Invited Speaker Wei-Ning Hsu**

15:30 - **Invited Speaker Zhifeng Kong**

16:00 - **Afternoon Break**

16:20 - **Contributed Talk - Speech De-warping: Unsupervised Pre-training for Data-Efficient Text-to-Speech on Low Resource Languages**

16:40 - **Contributed Talk - DiffGAN-TTS: High-Fidelity and Efficient Text-to-Speech with Denoising Diffusion GANs**

17:00 - **Panel Discussion**: Panel of invited speakers, where a moderator will facilitate discussion, including questions from the audience. 

### Call for Papers

We are calling for extended abstracts up to 4 pages excluding references. Several submissions will be chosen for 15-minute contributed talks and the remaining selected submissions will participate in the poster & demo session. Please make sure submissions adhere to the ICML format. Submit your work via CMT. The review process will be double-blind so please make sure not to put any author information in your submission.

Authors may also submit supplementary materials along with their papers if they wish (e.g., a preview of a potential demo). Reviewers will not be required to read/view/listen to said supplementary material. 

**Timeline**

* **Submission deadline (main paper & all supplementary material)**: EXTENDED TO May 31, 2022 AOE

* **Accept/reject notification date**: June 13, 2022

* **Camera-ready deadline**: July 8, 2022


Researchers submitting to our workshop may also be interested in [The ICML Expressive Vocalizations (ExVo) Workshop and Competition](https://www.competitions.hume.ai/exvo2022). Generative models submitted to our workshop could potentially be submitted to their ExVo Generate subtask, which asks participants to produce vocal bursts associated with 10 distinct emotions. The submission deadline for the challenge is June 1, 2022. See the link for more details.

### Invited Speakers
**[Chris Donahue](https://scholar.google.com/citations?user=MgzHAPQAAAAJ&hl=en&oi=ao)** (Google)

**Area of Interest**: generative modeling of audio and other sequential data, building real-world interactive music systems

**Talk Title**: Frontiers and challenges in music audio generation

**Abstract**: Despite notable recent progress on generative modeling of text, images, and speech, generative modeling of music audio remains a challenging frontier for machine learning. A primary obstacle of modeling audio is the extreme sequence lengths of audio waveforms, which are impractical to model directly with standard methods. A challenge more specific to modeling music audio is scaling to critical capacity, an elusive threshold of model size beyond which coherent generation emerges. In this talk, I will present strategies from my work which seek to overcome the practical challenges of modeling audio by either (1) exploring featurizations which reduce superfluous information in waveforms, or (2) proposing new methods which can process waveforms directly. I will also share insights from ongoing work on achieving critical capacity for generating broad music audio, i.e., music audio not constrained to a particular instrument or genre.


**[Wei-Ning Hsu](https://scholar.google.com/citations?hl=en&user=N5HDmqoAAAAJ)** (Facebook)

**Area of Interest**: representation learning, structured generative modeling, self-supervised learning for speech through leveraging varieties of weak supervision and different modalities

**Talk Title**: Self-supervised learning for speech generation

**Abstract**: Self-supervised learning (SSL) for speech has demonstrated great success on inference tasks such as speech recognition. However, it is less studied for generative tasks where the goal is to synthesize speech. In this talk, I will share our recent work on building unconditional and conditional generative speech models leveraging SSL. Instead of representing speech with traditional features like spectrogram, we showed that discrete units derived from self-supervised models serve as better generative modeling targets for several tasks. Specifically, we presented the first text-free spoken language models for prosodically rich speech as well as spoken dialogues, and achieved SOTA performance on speech-to-speech translation without intermediate text output.


**[Zhifeng Kong](https://scholar.google.com/citations?user=V_oa_q8AAAAJ&hl=en&oi=ao)** (UC San Diego)

**Area of Interest**: Deep Generative Learning

**Talk Title**: DiffWave: A Versatile Diffusion Model for Audio Synthesis

**Abstract**: DiffWave is a versatile diffusion probabilistic model for conditional and unconditional waveform generation. The model is non-autoregressive, and converts the white noise signal into structured waveform through a Markov chain with a constant number of steps at synthesis. DiffWave produces high-fidelity audios in different waveform generation tasks, including neural vocoding conditioned on mel spectrogram, class-conditional generation, and unconditional generation. DiffWave matches a strong WaveNet vocoder in terms of speech quality (MOS: 4.44 versus 4.43), while synthesizing orders of magnitude faster. In particular, it significantly outperforms autoregressive and GAN-based waveform models in the challenging unconditional generation task in terms of audio quality and sample diversity.


[Mirco Ravanelli](https://scholar.google.com/citations?hl=en&user=-6Pj3IYAAAAJ) (Concordia/MILA)

**Area of Interest**: deep learning, speech recognition, far-field speech recognition, robust acoustic scene analysis, cooperative learning, unsupervised learning

**Talk Title**: Cooperative Conversational AI

**Abstract**: The development of machines that effectively converse with humans is a challenging problem that requires combining complex technologies, such as speech recognition, dialogue systems, and speech synthesis.

Current solutions mainly rely on independent modules combined in plain unidirectional pipelines. To reach higher levels of human-computer interactions, we have to radically rethink current conversational AI architectures with a novel cooperative framework. We need to replace standard pipelines with "cooperative networks of deep networks" where all the modules automatically learn how to cooperate, communicate, and interact. This keynote will discuss some novel ideas toward this ambitious goal and will introduce a novel toolkit called SpeechBrain designed to easily implement this holistic approach to Conversational AI.


[Gus Xia](https://scholar.google.com/citations?user=h8-nXFcAAAAJ&hl=en&oi=ao) (Music X Lab NYU)

**Area of Interest**: Interactive intelligent systems to extend human musical creation and expression.

**Talk Title**: A hierarchical representation learning approach for source separation, transcription, and music generation.

**Abstract**: With interpretable music representation learning, music source separation problems are well connected with transcription problems, and transcription problems can be transformed into music arrangement problems. In particular, Gus will discuss two recently developed models. The first one used a pitch-timbre disentanglement to achieve source separation, transcription, and synthesis. The second one used cross-modal chord-texture disentanglement to solve audio-to-symbolic piano arrangement. In the end, Gus will show his vision of a unified hierarchical representation-learning framework that bridges music understanding and generation.

### Accepted Papers
[Generating Detailed Music Datasets with Neural Audio Synthesis](MLAS_Music_Datasets.pdf)
Yusong Wu, Joshua Gardner, Ethan Manilow, Ian Simon, Curtis Hawthorne, Jesse Engel

[Adversarial Audio Synthesis with Complex-valued Polynomial Networks](MLAS_Complex_Poly.pdf)
Yongtao Wu, Grigorios Chrysos, Volkan Cevher

[Speech De-warping: Unsupervised Pre-training for Data-Efficient Text-to-Speech on Low Resource Languages](MLAS_Speech_Dewarping.pdf)
Myungseo Song, Seongyeon Park, bohyung kim, Tae-Hyun Oh

[DrumGAN VST: A Plugin for Drum Sound Analysis/Synthesis with Autoencoding Generative Adversarial Networks](MLAS_DrumGAN_VST.pdf)
Javier Nistal, Cyran Aouameur, Ithan Velarde, Stefan Lattner

[DiffGAN-TTS: High-Fidelity and Efficient Text-to-Speech with Denoising Diffusion GANs](MLAS_DiffGAN-TTS.pdf)
Songxiang Liu, Dan Su, Dong Yu

### Organizers
[Sadie Allen](https://scholar.google.com/citations?user=LrmTlQwAAAAJ&hl=en&oi=ao) is a PhD student studying computer engineering at Boston University. Her current research is focused on generating music with long term structure in both the symbolic and raw audio domains. Her previous work centered around the security and efficiency of distributed systems.

Email: [sadiela@bu.edu](mailto:sadiela@bu.edu)

[Sander Dieleman](https://benanne.github.io/) is a Research Scientist at DeepMind in London, UK, where he has worked on the development of AlphaGo and WaveNet. His research is currently focused on generative modelling of perceptual signals at scale, including audio (speech & music) and visual data. He has previously co-organised four editions of the NeurIPS workshop on machine learning for creativity and design (2017-2020) and three editions of the Recsys workshop on deep learning for recommender systems (DLRS 2016-2018). 

Email: [sedielem@google.com](sedielem@google.com)

[Brian Kulis](https://scholar.google.com/citations?hl=en&user=okcbLqoAAAAJ) is an associate professor at Boston University and an Amazon Scholar working at Alexa AI.  His research focuses broadly on machine learning, recently focused on applications to audio problems such as detection and generation.  He has won two best paper awards at ICML and a best paper award at CVPR. He has previously organized two workshops at ICCV (in 2011 and 2013), one workshop at NeurIPS (in 2011), and one workshop at ICML (in 2019).  He is regularly an area or senior area chair at major AI conferences, was the local arrangements chair for CVPR in 2014, and has organized tutorials at ICML and ECCV.

Email: [bkulis@bu.edu](bkulis@bu.edu)

[Rachel Manzelli](https://scholar.google.com/citations?hl=en&user=BzMNxvoAAAAJ) is a research engineer at Modulate, where she works on both audio generation and classification models to assist video game moderation teams in decreasing toxicity in voice chat. She earned her bachelor's degree in computer engineering from Boston University in 2019. During her undergraduate career, she conducted research in the areas of structured music generation and MIR.

Email: [rachel@modulate.ai](mailto:rachel@modulate.ai)


[Yu Zhang](https://scholar.google.com/citations?user=EilVnKwAAAAJ&hl=en&oi=sra) is currently a research scientist at Google Brain. He received his Ph.D degree in computer science from Massachusetts Institute of Technology in 2017. During his Ph.D, he worked on improving speech recognition performance. He is a fan of open source projects and contributed or involved to develop CNTK, MXNet, and ESPNet to facilitate ASR research. Currently, his research interests are improving ML model performance for various speech processing applications, with a focus on sequence to sequence modeling. Yu is a main contributor to Google's next generation RNNT ASR model and Tacotron based text-to-speech system. 

Email: [ngyuzh@google.com](mailto:ngyuzh@google.com)

