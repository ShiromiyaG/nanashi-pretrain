# v1.5 (Rigel Version):

Same dataset and training method, but the finetune was done in Rigel 32k

Link: https://huggingface.co/shiromiya/nanashi-pretrain/tree/main/v1.5_(Rigel_Version)


# v1.5:
I changed from finetune on Titan to finetune on the original pretrain and with a slightly larger dataset

**Epoch:** 50

**Batch Size:** 16

**Dataset Length:** 10 hours of Brazilian singing voices

**F0 pitch extraction:** RMVPE

**Sample Rate:** Only 32k

**FP32**

**Fine-tune on Original Pretrain**

**Link:** https://huggingface.co/shiromiya/nanashi-pretrain/tree/main/v1.5

**Model made with this pretrain:**
[model](https://discord.com/channels/1159260121998827560/1263170120143077417) (AI HUB Discord Server)

# v1:
I made this model in the hope of improving the Brazilian accent in the AI models (But I believe it works with other languages without any problems), especially when singing (It may work for the speech models, but I'm not interested in trying it out). And as a test in general.

**Epoch:** 50

**Batch Size:** 16

**Dataset Length:** 9 hours of Brazilian singing voices

**F0 pitch extraction:** RMVPE

**Sample Rate:** Only 32k

**FP16**

**Fine-tune on Titan Medium**

**Link:** https://huggingface.co/shiromiya/nanashi-pretrain/tree/main/v1

**Model made with this pretrain:**
[model](https://discord.com/channels/1159260121998827560/1254196145492856976)  (AI HUB Discord Server)
