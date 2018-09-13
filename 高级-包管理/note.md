# 1. 模块
- 一个模块就是一个包含Python代码的文件， 后缀成员是.py就可以，模块就是个Python文件
- 为什么使用模块
    - 程序太大，编写维护是非不便，需要拆分
    - 模块可以增加代码重复利用的方式
    - 当作命名空间使用，避免命名冲突
- 如何定义模块
    - 模块就是一个普通文件，所以任何代码可以直接书写
    - 不过根据模块的规范，最好在模块中编写以下内容
        - 函数（单一功能）
        - 类 （相似功能的组合，或者类似业务模块）
        - 测试代码
        
- 如何使用模块
    - 模块之间导入
        - 假如模块名称直接以数字开头，需要借助importlib帮助
    - 语法
        import module_name
        module_name.function_name
        module_name.class_name
    - 案例 p01,p02
    - import 模块 as 别名
        - 导入的同时给模块起一个别名
        - 其余用法和第一种相同
        - 案例p03
    - from module_name import func_name, class_name
        - 按上述方法有选择性的导入
        - 案例 p04