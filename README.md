# pycharm-excise
# '''用python设计一个小游戏'''
# import random
# counts=3
# answer=random.randint(1,10)
# while counts>0:
#     guess=int(input('不妨猜猜王帅哥心里想的是哪个数字？'))
#     if guess==answer:
#         print("你是小甲鱼心里的蛔虫吗？")
#         print("猜中了也没有奖励！")
#         break
#     else:
#         if guess<answer:
#             print('猜小了！')
#         else:
#             print("猜大了!")
#     counts=counts-1
# print('游戏结束不玩了！')

# def temp_conversion(c):
#     f=c*1.8+32
#     return f
# c=float(input("请输入摄氏度："))
# f=temp_conversion(c)
# print("转化成的华氏度是"+str(f))

# score=int(input("请输入考试分数："))
# level=("D" if score<60 else
#        "C"if 60<=score<80 else
#        "B"if 80<=score<90 else
#        "A"if 90<=score<100 else
#        "S"if 100==score else
#        "请输入0-100之间的数")
# print(level)

# age=18
# isman=True
# print("未满十八岁，禁止访问！")if age<18 else print("本店商品任君选购！") if isman else  print("本店商品可能不适合您哦！")

# i=1
# sum=0
# while i<=1000000:
#     sum=sum+i
#     i=i+1
# print(sum)
# while True:
#     answers=input("主任我能结束了吗？")
#     if answers=="yes":
#         break
#     print("好嘞")

# day=1
# while day<=7:
#     answer=input("今天有好好学习吗？")
#     if answer!="有":
#         break
#     day+=1
# else:
#     print("非常棒，你已经坚持了七天")

# i=1
# while i<=9:
#     j=1
#     while j<=9:
#         print(j,'*',i,'=',j*i,end=" ")
#         j+=1
#     print()
#     i+=1

# for n in range(2,10):
#     for x in range(2,n):
#         if n%x==0:
#             print(n,'=',x,'*',n//x)
#             break
#     else:
#         print(n,"是一个素数")

# nums=[2.6,4,1,8,6,2,2,4,3]
# nums.sort(reverse=True)
# df=nums.count(4)
# print(df)

# matrix=[[1,2,3],[4,5,6],[7,8,9]]
# # matrixs=[element for row in matrix for element in row]
# # print(matrixs)

# df=[[x,y] for x in range(10) if x%2==0 for y in range(10) if y%3==0]
# print(df)

# words=["extremely","schedule","ture","firstrow","nums"]
# f=[w for w in words if w[0]=="f"]
# print(f)
# '''创建字典'''
# score={'name':'zhangsan','liisi':0}
# print(type(score))
