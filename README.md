# BUPT-Report-Typst
这里是专为北邮同学们打造的实验报告模板～（是根据DSP实验制作的！）

首页自带北邮LOGO和优雅的个人信息栏，~~不过LOGO有点糊，~~找机会在更新吧……😅

LOGO已经改了！

> [!IMPORTANT]
> 虽然已经尽量按照学校的Word模板来排版啦，但细微处可能有偏差……
> 如果老师是细节控本控，使用时请多留意哦～

字体基本格式
- [x] 一级标题，黑体+Times New Roman，四号，加粗
- [x] 二级标题，黑体+Times New Roman，小四号，加粗
- [x] 正文，宋体+Times New Roman，小四号，多倍行距1.2，首行缩进2字符，两端对齐等
- [x] 题注仿宋+Times New Roman，小五号

我的补充(主要是对照docx格式补充的)
- [x] 二级标题的缩进
- [x] 代码的缩进
- [x] 标题行间距相关情况

Fix:
- [x] 在插入图片/表格时出现缩进重置的问题

使用样例：
```typst
#import "@preview/simple-bupt-report:0.1.1": experiment-report

#show: doc => experiment-report(
  title: "《信号处理实验》实验报告",
  semester: "2024-2025学年第二学期",
  class: "2023211113",
  name: "张三",
  student-id: "2021123456",
  date: "2024年4月14日",
  doc
)
...(表示正文内容)
```

祝你实验顺利啦～✨

>（PS：如果遇到排版错误，欢迎来issue区和我分享）
