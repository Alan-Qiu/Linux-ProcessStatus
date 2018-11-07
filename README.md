# Linux-ProcessStatus
操作系统课程作业(显示linux所有进程)

在源文件目录下：
	<br>make</br>
	<br>sudo insmod print.ko</br>
	<br>lsmod</br>
	<br>sudo rmmod print</br>
即可编译源文件并添加内核模块，通过lsmod可以看到所有模块的信息，rmmod移出模块。

继续：
	<br>gcc -o a.out UserPrint.c -lpthread</br>
	<br>./a.out</br>
即可显示在console中。
