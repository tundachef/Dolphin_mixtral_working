# Dolphin_mixtral_working

[Run this colab file](https://colab.research.google.com/drive/1H0Ufkgy5E_ljVgplKWLVTrytTT0UHBHZ#scrollTo=LGQ8BiMuXMDG)

Go to the Model tab
Put this to download [TheBloke/dolphin-2.2.1-mistral-7B-GPTQ](https://huggingface.co/TheBloke/dolphin-2.2.1-mistral-7B-GPTQ)

## MUST 
ALWAYS SET AUTO-LOAD MODEL TO TRUE

### Then
Go to Default tab, in the input section then paste this: 
```
<|im_start|>system
{system_message}<|im_end|>
<|im_start|>user
{prompt}<|im_end|>
<|im_start|>assistant
```


