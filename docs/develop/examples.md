# 示例一
有一些人来参加宴会，但是宴会规定，只有名字叫卜星星的才能吃饭及进行一些其它活动  
这时候有两种写法  
* 第一种
```
names = ['lisi', 'wanger', 'buxingxing', 'zhangsan', 'buxingxing']
for name in names:
    if name == 'buxingxing':
        print(f"{name}可以吃饭")
        # TODO
```

* 第二种
```
names = ['lisi', 'wanger', 'buxingxing', 'zhangsan', 'buxingxing']
for name in names:
    if name != 'buxingxing':
        continue
    print(f"{name}可以吃饭")
    # TODO
```
> 如果是我，就会写成第二种，因为我认为这样写逻辑会更清晰，并且代码结构要更好看  