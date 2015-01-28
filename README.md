射手字幕校对
-----------------------------------


#字幕分配
http://subhd.com  
每天开始前商量好。


#字幕文件编码
用 Notepad++ 编辑。  
转成 UTF-8 无 BOM：  
![alt utf8](https://raw.github.com/wip-lab/shooter-calibration/master/utf8.png)

#修改规则
一个目录对应一个视频的字幕，多了删掉或另建目录，目录名为下载页面 URL  中的 id。目录里只留中英 2 个 srt，或一个双语 srt。
 * 对于 2 个 srt 分开的，中英每个一行，一一对应。文件名 *.chs.srt, *.eng.srt。
 * 对于单 srt 双语的，一行中一行英。
 * 时间轴、序号不用管。

#字幕错误类型
 * ~~错别字，拼写错误~~
 * 中文加了额外解释
 * 漏翻译
 * 句子部分错位
 * 整句错位
 * 特殊字符  
 
 若遇到其它错误类型，在群里讨论。

#提交方式
开个 GitHub repo，一人一个 branch。
用  GitHub for Windows。

每个字幕至少 2 次 commit
 1. 改了名的原始字幕(init 2121221)
 2. 校准完毕的字幕(done 2121221)  
 
每天至少 sync 一次



