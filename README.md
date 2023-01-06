# 22AA_project

高级算法：装箱问题

<title></title><style>
@font-face{
font-family:"Times New Roman";
}
@font-face{
font-family:"宋体";
}
@font-face{
font-family:"等线";
}
@font-face{
font-family:"Wingdings";
}
p.MsoNormal{
mso-style-name:正文;
mso-style-parent:"";
margin:0pt;
margin-bottom:.0001pt;
mso-pagination:none;
text-align:justify;
text-justify:inter-ideograph;
font-family:等线;
mso-bidi-font-family:'Times New Roman';
font-size:10.5000pt;
mso-font-kerning:1.0000pt;
}
span.msoIns{
mso-style-type:export-only;
mso-style-name:"";
text-decoration:underline;
text-underline:single;
color:blue;
}
span.msoDel{
mso-style-type:export-only;
mso-style-name:"";
text-decoration:line-through;
color:red;
}
table.MsoNormalTable{
mso-style-name:普通表格;
mso-style-parent:"";
mso-style-noshow:yes;
mso-tstyle-rowband-size:0;
mso-tstyle-colband-size:0;
mso-padding-alt:0.0000pt 5.4000pt 0.0000pt 5.4000pt;
mso-para-margin:0pt;
mso-para-margin-bottom:.0001pt;
mso-pagination:widow-orphan;
font-family:'Times New Roman';
font-size:10.0000pt;
mso-ansi-language:#0400;
mso-fareast-language:#0400;
mso-bidi-language:#0400;
}
@page{mso-page-border-surround-header:no;
 mso-page-border-surround-footer:no;}@page Section0{
}
div.Section0{page:Section0;}</style>

物流公司在流通过程中，需要将打包完毕的箱子装入到一个货车的车厢中，为了提高物流效率，需要将车厢尽量填满。

设车厢为长方形，其长宽高分别为L，W，H；共有n个箱子，箱子也为长方形，第i个箱子的长宽高为li，wi，hi（n个箱子的体积总和是要远远大于车厢的体积），做以下假设和要求：

1. 长方形的车厢共有8个角，并设靠近驾驶室并位于下端的一个角的坐标为（0,0,0），车厢共6个面，其中长的4个面，以及靠近驾驶室的面是封闭的，只有一个面是开着的，用于工人搬运箱子；

2. 需要计算出每个箱子在车厢中的坐标，即每个箱子摆放后，其和车厢坐标为（0,0,0）的角相对应的角在车厢中的坐标，并计算车厢的填充率。

基础部分：

- [x] 所有的参数为整数；

- [x] 静态装箱

- [x] 所有的箱子全部平放，即箱子的最大面朝下摆放；

- [x] 算法时间不做严格要求，只要1天内得出结果都可。

高级部分：

- [x] 参数考虑小数点后两位；

- [x] 实现在线算法，也就是箱子是按照随机顺序到达，先到达先摆放；

- [ ] 需要考虑箱子的摆放顺序，即箱子是从内到外，从下向上的摆放顺序；

- [x] 因箱子共有3个不同的面，所有每个箱子有3种不同的摆放状态；

- [x] 算法需要实时得出结果，即算法时间小于等于2秒。

额外功能

- [x] 可视化装箱
