# Script

1. `index.php`: 服务端测试脚本

2. [Script.conf](https://raw.githubusercontent.com/iepngs/Script/debug/Script.conf): 远程订阅配置文件

3. `debug.js`: 测试脚本


## 手动模拟请求触发脚本

> 可以用ios的捷径指令发起网络请求做调试（设置 > 快捷指令 > 勾选允许不受信任的快捷指令）

> 手机打开以下链接，点击获取捷径，自动跳转到捷径app中，然后打开后滚动到页面最底部，点击添加不受信任的快捷指令：

> [https://www.icloud.com/shortcuts/d7b7462beb4641caa4f581ce52b55531](https://www.icloud.com/shortcuts/d7b7462beb4641caa4f581ce52b55531)

> 在快捷指令列表上点击"模拟请求"右上角的三个点，进入详情页面上点右下角三角形运行可以看到结果，运行部分参考GIF


### 运行参数说明
> 更改捷径指令中注释下方的文本（变量uri），比如要请求`http://192.168.1.1:8998/102`,只需要把文本里的101改成102
> 捷径内已配置好测试的公网ip地址可直接做测试用。

### 捷径运行流程：
<img src="./3aa4c2cfdc03e166d6481ebfc21fea42.gif" width = "200" alt="" align=center />
