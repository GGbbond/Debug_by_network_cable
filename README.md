# Debug_by_network_cable
# 使用网线调试视觉板


# 第一步：

网线连接视觉板和电脑(电脑没有网口可以用type-c转网口转接头)

* 注：自己的电脑和被远程桌面的视觉板均需执行第一至四步，视觉板还需执行第五步


# 第二步：

打开设置 -> 选择“网络” -> 点击“已连接-1000Mb/秒”右边的小齿轮

![image](https://github.com/user-attachments/assets/f188f0d8-a2b3-4c7e-af1d-a9ed5dcb3fb3)


# 第三步：

选择"IPv4" 

-> 将“IPv4方式"设置为"手动" 

-> 设置"地址"为`192.168.2.6`(最后一个数可任意设置，视觉板与电脑上的数不同即可)

-> 设置“子网掩码”为`255.255.255.0` -> 点击“应用”

![image](https://github.com/user-attachments/assets/ca50244e-38d7-4e96-bb16-8e6ace87d99a)


# 第四步:

选择"设置"中的"共享" -> 将顶部右边的小按钮![image](https://github.com/user-attachments/assets/615f4969-fd21-4302-ac9a-91316f359768)
打开

![image](https://github.com/user-attachments/assets/f34b1a81-eb71-4ff2-8d17-b7df3ffe77f7)

点击"远程桌面" -> 打开"远程桌面"和"远程控制" -> 设置用户名和密码


# 第五步：

执行完上述步骤后已经可以使用，不过每次重新打开电脑后密码会自动改变

想要使密码保持不变，执行下面步骤：

找到"密码和密钥"

![image](https://github.com/user-attachments/assets/9805b49e-d0f8-4230-9ea4-716a68239f2a)

右键单击“默认密钥环” -> 选择“更改密码” -> 在输入新密码时不要输入，留着空白，然后继续。(可能会有警告，不过影响不大)

结束！
