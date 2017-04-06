# 二维码生成
###  利用二维码进行推广是app推广的一种常用手段
1.  导入zxing库![image](C:\Users\Administrator\Desktop\1491404337(1).jpg)
2. 利用BitMatrix进行矩阵转换
3. 调用ZXing库里面QRCodeWriter().encode的方法对我们传进去的URL进行编码
4. 按照二维码的算法，逐个生成二维码的图片，利用2个for循环对图片进行扫描
![image](C:\Users\Administrator\Desktop\1491405931.jpg)
5. 转成bitmap，并显示到一个ImageView上面
 ![image](C:\Users\Administrator\Desktop\1491406041(1).jpg)
