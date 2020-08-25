```python
#Pycharm使用技巧与调试
#自动补齐
#1.在pycharm中，你输入pr，它就会显示出候选项print()等，此时按一下tab键，就自动补齐了
#2.输入main，然后按tab键，就会补齐这种固定的形式
#这个表示，如果是本文件运行，就执行下方的语句，如果是被别的模块调用，就不执行
# if __name__ == '__main__':
#     print('Hello')

#打印本文件的名字
# print(__name__)

#3.可以自定义一些自动补齐的内容
#settings→Live templates ，点击右侧的+号，选第一个

#一般公司里面有各种版本管理工具，如svn,cvs,git等等
#右键选择一个文件，然后选择Local history，然后选中需要的版本，右键选择revert即可进行回退

#重构代码
#右键选择一个函数名或者变量名等，选择refactor，然后选择第二项
# def fun100(data1, data2):
#     return data1 + data2
# fun100(3, 6)

#shift+enter换行
#sadsagsafsadfgdgdgdfgggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggg

#修改函数的颜色
#settings→editor→color scheme→python→function call

#列表的排序，可以直接用现成方法，也可以用冒泡算法自己进行排序
# list1=[36,22,15,-1,9]
# list1.sort() #永久排序
# print(list1)
# print(sorted(list1)) #临时排序

#冒泡算法(可以通过调试查看中间过程)
# for i in range (0,len(list1)):
#     for j in range (0,len(list1)-1-i):
#         if list1[j]>list1[j+1]:
#             print(f'第{j}位和第{j+1}位的顺序是不对的，变化之前{list1},')
#             list1[j],list1[j+1]=list1[j+1],list1[j]
#             print(f'变化之后{list1}')
#         else:
#             print(f'{list1}顺序是对的，不用改')
#     print(f'第{i+1}轮循环结束')
# print(list1)

#思考题：用程序统计10000以内有多少个含有3的数
```