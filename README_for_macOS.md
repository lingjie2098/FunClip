# 安装
双击[`for_macOS_install.command`](for_macOS_install.command)。
# 运行
双击[`for_macOS_start.command`](for_macOS_start.command)
# 自定义配置
## imagemagick install
If you want to clip video file with embedded subtitles
>1.ffmpeg and imagemagick is required

```command
brew install imagemagick
sed -i 's/none/read,write/g' /usr/local/Cellar/imagemagick/7.1.1-8_1/etc/ImageMagick-7/policy.xml
```

>2.Download font file to funclip/font

```
wget https://isv-data.oss-cn-hangzhou.aliyuncs.com/ics/MaaS/ClipVideo/STHeitiMedium.ttc -O font/STHeitiMedium.ttc
```