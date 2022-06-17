
## vector

+ decide origin
+ A two-dimensional vector is a point in the plane relative to the origin
+ Adding a vector has the effect of moving or translating an existing point or collection of points.
+ x+(-y) 向量相减
    + 标量为x到y的距离
+  axes(rulers)
    + x-axis
    + y-axis

+ rule
    + tip-to-tail addition
## trigonometric
+ `tan(π/4 radian)=1`
    + `1 radian = 57.296 degree`
    + `π radians = 180 degree`
    + `π/4 radians = 45 degree`
    
## dot product
+ 通常用于计算两个三维向量的夹角
+ u.v=|u|.|v|.cos(ø)
    + ø 为u,v的夹角
+ return a scalar
    + 分别相乘再相加
+ 正数
    + aligned
    + 俩向量夹角小于90度
+ 负数
    + 俩向量夹角大于90度
+ 0
    + 俩向量垂直
```py
from math import cos,pi
# python中使用的是弧度
cos(75*pi/180)
```
## cross product
+ UxV=(UyVz-UzVy,UzVx-VzUx,UxVy-UyVx)
    + u v向量组成的平面的方向
+ return new vector
+ 
## tips
+ tan(tangent,切线) 比例的方式表示角度
+ polar coordinates
    + length,angle
    + 旋转
+ Cartesian coordinates
    + x,y
    + 平移




