# magazine

用以实现「英语外刊导读」副业

#### 目录介绍

* src/economist -> 《经济学人》
* src/time      -> 《时代》
* ...

各篇文章独立文件夹，命名格式为：

`$date_$title`

各篇文章至少存在素材：

* cover.png     -> 文章封面
* article.md    -> 文章内容
* speech.mp3    -> 英语配音（by AI）

成品：

* docx          -> 基于 template.docx 制作，最终导出为 pdf，供读者阅读。
* mp4           -> 用于发布到 bilibili
    1. 由于 mp4 巨大，不上传到 git 仓库。
