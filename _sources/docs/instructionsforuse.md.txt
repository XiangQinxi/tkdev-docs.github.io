# 使用说明

---

## 导入注意实现
按照传统库名，导入的名字应该和tkinterDev库名一样，叫做tkinterDev导入，可是发现这个名字太长了就将它改名为tkdev。
所以我们需要按照一下代码进行导入
```python
import tkdev
```
并且如果你想以`from tkdev import xxx`导入时，请不要使用`from tkdev import *`因为如果与其它库的组件名称相同的话，可能会出现无法估计的后果。