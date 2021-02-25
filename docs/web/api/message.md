# Message 全局提示

对用户的操作作出轻量的全局反馈。

### 何时使用

在完结某个独立页面后的反馈（如：付款成功页面）；

在一个操作区域或一系列操作完成之后的总体反馈（如：提交分步骤表单中的某个表单）；

在某个操作点之后的反馈（如：针对信息复制操作的结果反馈）。


## 1.组件类型

常规全局提示包含：普通信息、成功信息、警示信息、错误信息、帮助信息和loading。

### 1.1.提示信息

{{ base }}

### 1.2.成功信息

{{ success }}

### 1.3.警示信息

{{ warning }}

### 1.4.错误信息

{{ error }}


### 1.5.帮助信息

提供简短的帮助信息提示。

{{ help }}

### 1.6.loading

提供全局的加载过程反馈，需要提供加载结果：成功、失败。

{{ loading }}