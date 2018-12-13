# sed

### 又称流编辑器\(vi为交互式编辑器\)

命令格式:

```bash
sed  options script file
```

#### 1.替换

```bash
sed 's/old/new/'
eg: echo 'abcd addd' | sed 's/a/z/'
```

![](/assets/import.png)

发现了吗? 参数`g` 为`global`意为全局修改, 不加参数`g`则只替换第一个匹配值\(每条流\)

![](/assets/import1.png)

#### 2.





