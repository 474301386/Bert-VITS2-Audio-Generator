# Bert-VITS2-Audio-Generator
GUI TTS application based on:

Bert-VITS2 (https://github.com/fishaudio/Bert-VITS2)

PyQt-Fluent-Widgets (https://github.com/zhiyiYo/PyQt-Fluent-Widgets).

![app](https://github.com/FeRain-FR/Bert-VITS2-Audio-Generator/assets/151917667/4c33f7ae-17d7-4d41-94d0-317aefde67a6)

## Install
- **Bert-VITS2-Audio-Generator.zip**

  [Download Here](https://drive.google.com/file/d/1Xk2m4nVYMdHGU2ZSQDQT2kmefFMdUEex/view?usp=drive_link) (Google Drive)

> Suitable for who knows nothing about the deployment of Bert-VITS2.
> 
> Download, Extract, Run app.exe

> 適合對Bert-VITS2部署一無所知的朋友。
>
> 下載，解壓，運行 app.exe
#

- **Bert-VITS2-Audio-Generator_withoutLargeModelFiles.zip**

  [Download Here](https://github.com/FeRain-FR/Bert-VITS2-Audio-Generator/releases/download/v1.0/Bert-VITS2-Audio-Generator_withoutLargeModelFiles.zip)

Large model files:

![largefiles](https://github.com/FeRain-FR/Bert-VITS2-Audio-Generator/assets/151917667/0e24c2e2-416c-420b-ad47-4fe354c4c288)

bert/chinese-roberta-wwm-ext-large/pytorch_model.bin: [Download Link](https://huggingface.co/hfl/chinese-roberta-wwm-ext-large/resolve/main/pytorch_model.bin?download=true)

bert/deberta-v2-large-japanese/pytorch_model.bin: [Download Link](https://huggingface.co/ku-nlp/deberta-v2-large-japanese/resolve/main/pytorch_model.bin?download=true)

bert/deberta-v3-large/pytorch_model.bin: [Download Link](https://huggingface.co/microsoft/deberta-v3-large/resolve/main/pytorch_model.bin?download=true)

</br>

> Suitable for who has already deployed Bert-VITS2 locally.
>
> Move the pytorch_model.bin files to correct places, then Run app.exe
> 
> **(Note that NOT to rename the .bin files and DO NOT mix them up)**

> 適合已經本地部署Bert-VITS2的朋友。
>
> 將以上幾個pytorch_model.bin文件放到正確的位置，然後運行app.exe
> 
> **(注意請不要更改文件名字，也不要把它們弄混)**

</br>

The location of bert:

![bert](https://github.com/FeRain-FR/Bert-VITS2-Audio-Generator/assets/151917667/4d3061b8-8cf7-4696-887a-93675c3a17f3)
#
- **Source Code**

  [Download as zip](https://github.com/FeRain-FR/Bert-VITS2-Audio-Generator/archive/refs/tags/v1.0.zip)
  
  [Download as tar.gz](https://github.com/FeRain-FR/Bert-VITS2-Audio-Generator/archive/refs/tags/v1.0.tar.gz)

>Suitable for who is familiar with Python
>
>You have to download the large model files listed above
>
>requirements.txt is provided
>
>Run app.py

>適合熟悉Python的朋友
>
>需要自行下載上面所列的幾個模型文件
>
>已提供requirements.txt
>
>運行 app.py
#


