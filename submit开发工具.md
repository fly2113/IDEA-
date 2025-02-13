# submit开发工具使用

- 字体大小修改

  > 首选项->设置用户->修改font-size的值

- 代码高亮显示

  > 右下角选择对应的语言

- 设置文件编码

  > 文件->设置编码格式（命令窗口的编码格式是GBK所以在此窗口编译带有中文的java文件时需要把编码格式调整为GBK）
  
- Ctrl+/ ：注释快捷键

- Ctrl+Shift+D :复制光标选中的整行，插入到下一行

- 快捷键冲突修改

  > 首选项->按键绑定-默认->Ctrl+F调出搜索框（搜索需要更改的快捷键）->复制目标行代码到按键绑定-用户->修改快捷键->保存

# dos窗口使用

- 快速写文件名

  > 输入几个字母按Tab键自动补全

# 文档注释 javadoc标签

- 常用的javadoc标签

  > https://juejin.cn/post/7216142711614521402

- 使用命令

  > javadoc -d 文件夹名 -xx -yy java文件名

# Dos常用命令

- md + 文件路径

  > 创建文件夹

- rd + 文件路径

  > 删除文件夹

- dir + [文件路径 ]   查看当前目录下有什么

- cd + /当前盘符 + 目标盘符：   切换盘符

- cd + 路径    切换到当前盘的其他目录

- cd .. 返回上一级

- cd \ 切换到根目录

- tree + [文化路径]   查看此目录下的所有子目录以树的形式显示

- cls 清屏

- exit 退出DOS系统

- 了解拓展

  > copy:拷贝文件；del：删除文件;echo：输出内容到文件；move:剪切

# 开发小工具

- java1.8中文在线文档：https://www.matools.com/api/java8
- Unicode在线转换：https://tool.chinaz.com/Tools/Unicode.aspx
- ASCII码表：https://c.biancheng.net/c/ascii/
- Javap的使用：https://www.cnblogs.com/baby123/p/10756614.html

# IDEA使用技巧和经验

https://www.bilibili.com/video/BV1fh411y7R8?t=474.5&p=266

> ## 新建项目
>
> >  新建项目选择路径后要在路径后面加上\和项目名称
>
> ## 项目目录
>
> - src文件夹存放源码
>
>   > 在src文件夹新建java class文件



- 设置字体

  > 界面文字大小：file->settings->appearance
  >
  > 代码大小：菜单file->settings->Editor->Font 

- 颜色主题

  > file->settings->Editor->Color Scheme

- 设置字符编码

  > file->settings->Editor->File Encodings
  
- 设置F7进入Debug源码

  > 点击Setting --> Build,Execution,Deployment --> Debugger --> Stepping
  > 把Do not step into the classes中的java**.*，javax.*取消勾选，其他的随意

# IDEA常用快捷键

- 设置快捷键

  > file->settings->Key map(搜索快捷键)->自行更改

- 删除当前行(搜索关键字：delete)

  > Ctrl+D

- 复制当前行(搜索关键字：duplicate)

  > Ctrrl+ALt+向下箭头

- 补全代码

  > alt+\

- 添加注释和取消注释

  > Ctrl+/

- 导入该行需要的类

  > 先配置自动导入：file->setttings->Editor->General->Auto Import
  >
  > 然后使用快捷键:alt+enter

- 快速格式化代码

  > ctrl+Alt+L

- 快速运行程序

  > alt+R

- 重写toString方法

  > alt+insert选择toString(输出对象信息)

- 生成构造器(构造方法)

  > alt+insert 选择Constructor

- 封装快捷键

  > alt+insert 选择Getter and Setter

- 查看一个类的继承关系

  > ctrl+H

- 定位方法是哪一个类

  > ctrl+B

- 自动分配变量名

  > 通过在后面加上.var
  >
  > 举例：new Scanner(System.in).var

# IDEA模板/自定义快捷键

## 自定义模板设置

> file->settings->editor->Live templates

- sout

  > ```
  > System.out.println();
  > ```

- fori

  > ```
  > for (int i = 0; i < ; i++) {
  >     
  > }
  > ```

# 断点调试快捷键

- F7（跳入）：跳入方法内

- F8（跳过）：逐行执行代码

- shift+F8（跳出）：跳出方法

- F9（resume，执行到下一断点）

  