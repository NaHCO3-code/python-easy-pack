# python-easy-pack
make pack up python files easier. 目前只提供了中文环境

# 如何使用?
1. 将`index.py`复制到你的项目文件夹，或者把.py文件拷贝到这个文件夹。
1. 打开你的cmd或者powershell
3. 切换到程序所在目录，输入`python index.py`来运行程序。当然，你直接双击运行index.py我也不会反对。
4. 按照要求输入。请注意：目前安装第三方库的功能还未完全完善（一点也不银杏），如果需要第三方库，建议手动在`./pyvenv-easypack/Script`目录里使用pip命令安装第三方库。
5. 请认真查看每一条要求输入的信息。这很重要，直接关乎打包的成功与否。
6. 打包完成并显示成功信息后，你可以在`./dist`文件夹里找到你想要的东西。