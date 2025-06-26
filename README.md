# 文件列表：
`tianzi_dict.pkl` - Lvory的自定义词典，`pickle`序列化的`dict[str, set[str]]`格式，键为词典名，值为词典内容
`word_dict.zlib_csv` - 整合了各大词库的一个词库，`zlib`压缩的`csv`格式，一行一词
# 上传注意事项
对于`word_dict`，**不要**上传`.pkl`_（`pickle`序列化后文件体积会显著增大）_ 或未压缩的`.csv`格式 _（因为不压缩的话文件太大了传不上来）_。请将其用`zlib`压缩后再上传。
