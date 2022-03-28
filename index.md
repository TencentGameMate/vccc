## VCCC: Voice Conversion via Cycle reconstruction and Contrastive learning 

Hongshen Sun, Peiji Yang, Xin Chen, Zhisheng Wang, Dongyang Qiu, Mingliang Liu and Lei Zheng

Tencent Groups

**Abstract**: Voice conversion (VC) aims to convert a particular source speaker's voice to sound like that of another target person while preserving the linguistic content unchanged. Though the evolution of deep learning has enabled great progress of VC, the conversion results are still not satisfactory in terms of both generation quality and speech similarity. To further improve the conversion results, we propose VCCC, a new training framework based on auto-encoder. Specifically, the cycle reconstruction process forces the model explicitly trained to convert speeches among different speakers, which mitigates the mismatch between training and inference significantly. Moreover, contrastive learning enables the speaker encoder to extract more appropriate features for the conversion task efficiently. The experiment results show that our approach is superior to the state of art models regarding to the conversion naturalness and similarity.

[![GitHub Stars](https://img.shields.io/github/stars/TencentGameMate/vccc)](https://github.com/TencentGameMate/vccc)
![visitors](https://visitor-badge.glitch.me/badge?page_id=TencentGameMate/vccc)

## Samples

1. sample_009_unseen_p308

|                         |                                                                                                          **wav** |
| ----------------------- | ---------------------------------------------------------------------------------------------------------------- |
| Source                  | ​<audio id="audio" controls="" preload="none"><source id="wav" src="mic/sample_009_unseen_p308/src.wav"></audio> | 
| Reference               | ​<audio id="audio" controls="" preload="none"><source id="wav" src="mic/sample_009_unseen_p308/ref.wav"></audio> |   
| Voice Conversion Result | ​<audio id="audio" controls="" preload="none"><source id="wav" src="mic/sample_009_unseen_p308/vc.wav"></audio>  |
