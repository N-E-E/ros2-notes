## 命令行常用指令



## 工作空间与功能包

- 一个项目中四个基本的文件
- 使用colcon build命令进行编译,编译前一定要先conda deactivate，不然会环境冲突
- 安装文件要进行环境变量配置,将iinstall/local_setup.sh放进bashrc中

### 创建功能包

```powershell
// 要在source下命令
ros2 pkg create --build-type ament_cmake learning_pkg_c
```

## 节点

### 节点使用流程

<img src="/home/yu/.config/Typora/typora-user-images/image-20221001220021491.png" alt="image-20221001220021491" style="zoom:50%;" />

### 编程方式

基于过程和面向对象

