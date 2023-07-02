## cmd
+ `jupyter-lab`

## code
+ `%load_ext autoreload`
    + IPython的魔术命令，在代码修改后自动重新加载模块
        + 修改了一个已经导入的模块的代码
    + %autoreload 0：禁用自动重新加载。
    + %autoreload 1：只重新加载模块中发生改变的部分。
    + %autoreload 2：重新加载模块的所有代码，包括模块中的函数和类。