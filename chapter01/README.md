# 布尔逻辑

本章主要是利用HDL实现布尔门，想要通过最基础的Nand进行推导的话，需要先熟知逻辑门的基本运算：

![gate_basic_logic](https://gitee.com/howie6879/oss/raw/master/uPic/2ztweY.png)

接下来介绍如何实现书中介绍的16个门。

## 基本逻辑门

### Not

描述：

![pxbaaP](https://gitee.com/howie6879/oss/raw/master/uPic/pxbaaP.png)

题解：
$$
\begin{align}
\bar{A} & = \overline{A \cdot A}
\end{align}
$$

### And

描述：

![iJLpKB](https://gitee.com/howie6879/oss/raw/master/uPic/iJLpKB.png)

题解：
$$
\begin{align}
A \cdot B & = \overline{\overline{A \cdot B}} & = \overline{\overline{A \cdot B} \cdot \overline{A \cdot B}}
\end{align}
$$


### Or

![g1idKr](https://gitee.com/howie6879/oss/raw/master/uPic/g1idKr.png)



$$
\begin{array}{c}
A+B=\overline{\overline{A+B}}=\overline{\bar{A} \cdot \bar{B}}
\end{array}
$$

### Xor

![aWcptw](https://gitee.com/howie6879/oss/raw/master/uPic/aWcptw.png)

题解：
$$
\begin{align}
A^{\wedge} B & = (A \cdot \bar{B})+(\bar{A} \cdot B)
\end{align}
$$

### Multiplexor

![FlxS2G](https://gitee.com/howie6879/oss/raw/master/uPic/FlxS2G.png)

![K8z9Mi](https://gitee.com/howie6879/oss/raw/master/uPic/K8z9Mi.png)

