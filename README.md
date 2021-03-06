# sublime-text3-conda-auto-complete-with-anaconda

![conda.git](https://github.com/thep0y/sublime-text-3-conda-auto-complete-with-anaconda/raw/main/images/conda.gif)

### English
Conda is a convenient virtual environment management plugin, but it cannot perform code auto-completion normally. 

In order to seamlessly complete the automatic completion when switching or activating the virtual, I made a small modification to the official Conda package. 

When switching to a new virtual environment, the python interpreter in the Anaconda user-settings will be modified at the same time to complete the automatic completion.



### 中文
Conda包是Anaconda官方出的sublime text 3插件，能够提供便捷的虚拟环境管理功能，但却与非Anaconda官方发布的Anaconda包并不兼容，使用Anaconda进行代码补全的人应该知道，这个插件非常好用。

于是，我就简单修改了一下Conda包，完成了在切换或激活虚拟环境时，Anaconda自动修改python解释器位置，能够实现在切换环境的同时无缝完成代码补全。


### 注意事项
在读取Anaconda的配置文件时，用的是json读取，但sublime text本身的配置并不是标准的json格式，注意最后一行参数不要的逗号，不然就会出错。

下一步，将会修复这个问题。


