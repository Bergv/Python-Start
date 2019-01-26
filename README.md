# Python-Start

## 1.Python安装相关

### pip源更新

windows下，直接在user目录中创建一个pip目录，如：C:\Users\xx\pip，新建文件pip.ini，内容如下

```ini
[global]
index-url = https://pypi.tuna.tsinghua.edu.cn/simple
[install]
trusted-host = mirrors.aliyun.com
```

### pip命令

```
python -m pip install -upgrade pip #先更新pip
pip install SomePackage
pip uninstall packageName
```

### 基本需要的库

```
pip install flake8 #安装flake8之后写代码的时候编辑器就会提示哪里出错，代码格式不规范也会提示
pip install yapf   #安装yapf之后在VScode中按Alt+Shift+F即可自动格式化代码
pip install pylint
```

### VS Code安装配置

##### 扩展：

```
Chinese (Simplified) Language Pack for Visual Studio Code
Python
Code Runner
Markdown All in One
Markdown Preview Enhanced
Markdown Theme Kit
```

##### 配置：

```json
{
​    "editor.fontSize": 18,
​    "editor.fontFamily": "YaHei Consolas Hybrid",
​    "markdown.preview.fontSize": 18,
​    "markdown.preview.fontFamily": "YaHei Consolas Hybrid",
​    "terminal.integrated.fontSize": 18,
​    "python.formatting.provider": "yapf",
​    "python.linting.flake8Enabled": true
}
```







