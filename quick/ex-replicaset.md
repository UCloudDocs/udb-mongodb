# 扩展副本集

云数据库MongoDB控制台默认一键副本集创建3个节点（1个primary+1个secondary+1个arbiter），同时提供增加节点的功能（比如：扩展至5节点、7节点等），用户可以根据业务需求情况增加Secondary节点和Arbiter节点数量。操作如下：

![image](/images/副本集节点.png)

选择所需的节点类型（arbiter节点免费），确认提交并支付成功，即完成节点创建：

![image](/images/节点列表.png)

当节点初始化完成，实例为运行状态时，可以对节点进行管理操作（如：配置升降级、关闭重启、删除等操作）。
