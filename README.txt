1.文件说明
include:
	存放头文件io.h,copy.h
lib:
	存放编译生成的.o函数
src:
	存放所有源文件
makefile:
	makefile文件
		
2.执行方法
1)确认系统环境
	Linux系统下，gcc编译器

2)运行测试
	把niitfujitsu文件放到工作目录下，运行make，即可使用niitfujitsu命令。

3.目录结构
niitfujitsu
|--README.txt
|--makefujitsu
|--niitfujitsu
|--include
   |--io.h
   |--copy.h
|--lib
|--src
   |--copy
      |--create_dir.c
      |--dircopy.c
      |--dircopydir.c
      |--filecopy.c
      |--filecopydir.c
   |--copy.c
   |--delete.c
   |--dirdelete.c
   |--dirplay.c
   |--file.c
   |--help.c
   |--help.txt
   |--list.c
   |--main.c
   |--mkdir.c
   |--symkink.c
