# 必要工具
+ [LSBSteg.py]:(http://github.com/RobinDavid/LSB-Steganography)
+ base64&图片转换

# 解水印步骤
1. 利用LSBSteg.py脚本得到隐藏的文本
```
python LSBSteg.py decode -i test.png -o info.txt
```
2. 将得到的文本内容以base64转图片得到水印图片

# 结论
+ 可以再对base64编码内容进行加密，隐藏base64转图片的线索
