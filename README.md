# 简介
提取 Excel 里的数据，导出为各种结构化的文本。除了提供命令行下的可执行脚本外也提供了
 Python API，但后续版本的兼容性不作绝对保证，请自备智慧与勇气。


# 繁介
你总会需要一些由非技术人员提供的数据来充实你的程序内容，比如美术资源和各种数值。美术资源好说，
规范好目录和文件名就万事大吉了，但数值咋放呢？必须得有一个他懂、你懂、程序也懂的数值载体，
除了 Excel 估计你也没得选了，总不能指望人家跑来编辑什么 json、xml 之类的结构化文本吧？何况
 Excel 本身也是个强大的数据处理工具，拿它来做数值易如反掌。于是本项目应运而生，专门用于提取
 Excel 里的二维数据，生成结构化的文本以供你的程序使用。

# 特性
 - 尽量约定而非配置，只需标出列名就能满足基本要求，高级玩法也只需要一点点小配置而已。 :stuck_out_tongue_winking_eye:
 - 支持多种数据结构 e.g. list,dict, （tree还有待实现）。
 - 支持导出为 json 格式

# 运行依赖

  * Python3
  * [xlrd](www.python-excel.org) >= 0.9
  * [docopt](http://docopt.org/) >= 0.6.0

# 安装
```bash
$ python setup install
```

# 使用

```bash
$ excel2json.py --help
```

# TODO

 - [x] 睡觉 :sleeping:
 - [x] 睡觉 :sleeping:
 - [ ] 睡觉 :sleeping:
 - [ ] 睡觉 :sleeping:
 - [ ] Python2.7 Support :stuck_out_tongue_winking_eye:
 - [ ] Simple DSL :stuck_out_tongue_winking_eye:
 - [ ] Export to Lua code :stuck_out_tongue_winking_eye:
 - [ ] Export to SQL code :stuck_out_tongue_winking_eye:

# 支持
<mailto:cupen@foxmail.com> :scream: noooooo!

# LICENCE  
<a href="http://www.wtfpl.net/">
    <img src="http://www.wtfpl.net/wp-content/uploads/2012/12/wtfpl-badge-1.png"
         width="88"
         height="31"
         alt="WTFPL" />
</a>
