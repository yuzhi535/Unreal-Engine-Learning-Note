# 关于cpp代码

---

[视频链接](https://www.youtube.com/watch?app=desktop&v=nVm-DYdAsts)


1. 模块用于写插件
2. 继承的一些父类

   1. actor类：比较普通的类。不能接受输入
   2. pawn类：比actor类高级一些，可以接受输入
   3. character类：比pawn类高级。顾名思义，除了可以接受输入，还自带了走路 跑步 跳跃等姿势。

3. 创建物体的函数: `CreateDefaultSubobject<>()`
4. 用宏`UPROPERTY(...)`来指示创建出来的变量的性质，如EditAnywhere, VisableAnywhere, category : ... 等等。例子：`UPROPERTY(EditAnywhere)`
