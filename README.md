

# Notebook

### Python

#### import路径

Python的import默认搜索路径查看：

```python
import sys
print(sys.path)
```

添加搜索路径方法：

1. sys.path.append()

2. 添加环境变量PYTHONPATH

3. 在site-packages下创建___.pth文件，文件中内容为添加的路径

   ```python
   ### 示例
   # windows
   F:\\xxxx\\xxxx
   # linux
   /home/user/xxxx/xxx
   ```

   

