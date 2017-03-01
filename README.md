# Eclipse的配置文件备份

org.eclipse.core.runtime/目录下是Eclipse选项的配置文件，其用法是：

> 将workspace/.metadata/.plugins/org.eclipse.core.runtime中的.settings文件夹拷贝出来，里面就是所有的配置文件，新建工作空间的时候将该.settings文件夹替换掉新工作空间中的.settings文件夹即可。

org.eclipse.e4.workbench/目录下是Eclipse布局的配制文件，其用法是：

> 将workspace/.metadata/.plugins/org.eclipse.e4.workbench文件夹保存起来。新建工作空间的时候将其还原即可。