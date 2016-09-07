# qrcode_win
 EXE version of [qrcode](https://github.com/sylnsfar/qrcode) for Windows (even without Python)

 EXE 版本的  [qrcode](https://github.com/sylnsfar/qrcode) ，适用于Windows系统（即使没有安装Python）

​        

## Introduction   介绍

* This is a `.exe` program working on Windows. When you don't want to setup Python or when you don't want to use commands, you can try it.

* Packed up with [PyInstaller](https://github.com/pyinstaller/pyinstaller).

* Original repository: [qrcode](https://github.com/sylnsfar/qrcode)

* **Attention 1**: This program is just a simple pack-up with unknown efficiency and stability. On some pc it's fast, and others slow.(don't know why)

* **Attention 2**: At first time to run, it may download some dependent files, which is because of the dependent module [imageio](https://pypi.python.org/pypi/imageio).

  ​      



* 这是一个运行在 Windows 系统的 `.exe` 程序。如果你不想安装 Python 或者不想使用命令行就可以试一下这个程序。
* 该程序使用 [PyInstaller](https://github.com/pyinstaller/pyinstaller) 打包而成。
* 原始仓库： [qrcode](https://github.com/sylnsfar/qrcode)
* **注意1**：该程序只是一个简单的打包，测试时，有的电脑快，有的电脑慢。(原因不明)
* **注意2**：第一次使用可能会自动下载一些库文件，原因是程序依赖的库 [imageio](https://pypi.python.org/pypi/imageio)。





## Usage   用法

### step 1 - info.txt

To use this program, you need to create a `.txt` file named `info.txt` which contains the arguments to generate QR-Code. The format is like this:	

运行此程序需要创建一个命名为 `info.txt` 的文本文件，里面写上用来生成二维码的所有参数。文件格式如下：

```python
# an example for info.txt:
words=https://github.com
v=10
l=Q
p=github_logo.png
c
con=1.5
bri=1.3
```

* **Important**: One argument, one line and no space at the both side of `=` . If a argument is useless, delete it. (words is neccesary)

  **重要**：一个参数一行，等号左右不要空格。如果不使用某个参数，则将其删去。（words是必要的）

* See  [qrcode](https://github.com/sylnsfar/qrcode) for the meaning and values of every argument and the results of this program.

  各个参数的含义和取值，以及结果效果图，请参考原代码地址： [qrcode](https://github.com/sylnsfar/qrcode)



​     

### step 2 -  Run it

After editing the `info.txt` file, put it into the folder where this program is (if there is a picture, put together too). Click the `myqr.exe` and wait for the result like:

编辑好`info.txt` 之后，就把它与程序放在同一文件夹（如果有图片，图片也放一起），双击 `myqr.exe` ，然后等待成功提示（如下）：

![](https://github.com/sylnsfar/qrcode_win/blob/master/test.png)

