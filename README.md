# 简单的验证码识别程序  
  
里面包含了500个训练样例和200个测试样例  
  
## Captcha.py  
一开始会提示你是否重新处理图片，如果是，则会将所有图片重新处理一遍，并重新训练模型，需要花费较多时间

模式1：爬虫得到一张新的验证码图片，并进行识别  
模式2：收集测试样例模式（得到100张图片，并需要自己输入答案，作为新的测试样例）  
模式3：测试所有的测试样例  
  
  
Eigenvalue: 用自己设定的特征值作为训练集  
Accurate: 直接用像素作为训练集  
  
  
Simple:直接遍历的方法，较慢
Model:用模型预测，较快

以后若有空就写到博客上去  
