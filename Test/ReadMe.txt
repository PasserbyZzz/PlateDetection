2.jpg 里面是一张用于测试的图片，运行脚本test.py, 切割出来的图片会保存在output1文件夹里面，同时在命令行里面输出对于图片的预测结果， 运行test.py需要： Final_LPRNet_model.pth（模型的数据）， config.js（切割图片的代码的信息）， 以及电脑中必要的pytorch环境（推荐以anaconda下载，python3.9及以上版本运行）最佳

此文件的模型，对于切割成功的图片，预测完全正确的概率为43%， 对于图片中的任意单个字符，预测正确概率为80%。 未来随着模型的进一步训练，效果应该会提升。
