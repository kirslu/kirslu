import turtle

# 设置画笔速度
turtle.speed(1)

# 初始化画笔位置
turtle.penup()
turtle.goto(0, -100)
turtle.pendown()

# 绘制爱心上半部分
turtle.color("red")
turtle.begin_fill()
turtle.left(140)
turtle.forward(180)
turtle.circle(-90, 200)
turtle.right(140)
turtle.circle(-90, 200)
turtle.forward(180)
turtle.end_fill()

# 绘制爱心下半部分
turtle.color("pink")
turtle.begin_fill()
turtle.left(140)
turtle.forward(180)
turtle.circle(90, 200)
turtle.right(140)
turtle.circle(90, 200)
turtle.forward(180)
turtle.end_fill()

# 隐藏画笔
turtle.hideturtle()

# 结束程序
turtle.done()
