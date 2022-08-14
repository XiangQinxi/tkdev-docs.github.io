# 快速开始
这是一个`Python库`，我已经上传到`pypi`上面，所以可以，使用pip来安装`tkinterDev`库。
```bash
pip install tkinterDev
```
我们也可以去[pypi](https://pypi.org/project/tkinterDev/)上面去找到想要的那个版本，
但是推荐使用最新的稳定版，因为这样会出的BUG会尽量少一点。

---

## 安装依赖库

等等，你是不是以为安装完了这个库就已经可以使用完整的库了吗？为了使用更完整的库，你可以去安装一些依赖库。
但是[我的网站](https://xiangqinxi.github.io/tkinterDev/%E5%AE%89%E8%A3%85/)里有讲解过，
你可以去[我的网站](https://xiangqinxi.github.io/tkinterDev/%E5%AE%89%E8%A3%85/)里去找到安装的。
但是如果你真的懒得去看，那我可以在这里写下来安装教程

---

### 可选安装
最主要的是pywin32库，这是最重要的，在其他的依赖库中也是需要依赖pywin32来开发的。所以按理来说应该是最需要安装的一个库

```bash
pip install pywin32
```
其次就是一些工具库了。tkinter-tooltip就是一个工具提示，将鼠标放在组件上可以显示提示。就直接做成了DevToolTip组件，主要是因为我懒
```bash
pip install tkinter-tooltip
```
之后是为了美观而设置的Mica云母特效和Acrylic亚克力特效。但是，如果你是Windows11以下的话就还是不要安装Mica特效库了。因为这个Mica库只支持Windows11。
```bash
pip install win32mica
```
```bash
pip install BlurWindow
```
最后就是用于检测系统主题的库了，darkdetect用于在使用界面特效时自动检测主题并选择为系统主题，以变成与系统相同的主题。
```bash
pip install darkdetect
```
可以用于截取窗口
```bash
pip install tkcap
```
----
### 一键安装
简单粗暴，使用tkinterDev库里的Install_ALL方法安装所有的依赖库。
但是如果这个方法报错，请将`报错信息`发到[我的邮箱](mailto:XiangQinxi@outlook.com)内，并且安装上面的方法进行安装即可。
```python
from tkdev import Install_ALL
Install_ALL()
```

```{note}

Install_ALL()默认使用的是清华大学的国内源。 如果需要，可以更改安装源，和是否启用安装源。只需要在方法中加入Basic参数，True代表使用安装源，False代表不使用安装源。如果要自定义源，就加入Pypi参数，可以调为想要使用的安装源

```