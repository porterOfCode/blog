# sed

### 又称流编辑器\(vi为交互式编辑器\),sed修改副本并进行输出,默认不修改原文件

命令格式:

```bash
sed  options script file
-f 读取脚本文件
-n
-e
```

#### 1.替换

```bash
sed 's/old/new/'
eg: echo 'abcd addd' | sed 's/a/z/'
```

![](/assets/import.png)

发现了吗? 参数`g` 为`global`意为全局修改, 不加参数`g`则只替换第一个匹配值\(每行\)

![](/assets/import1.png)

也可以实现多次修改

![](/assets/import2.png)

#### 2.



