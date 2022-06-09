# Chinese-English-PV-Test0
PV materials prediction via chinese and english


Output files such as word2vec0607.txt (English) and word2vec0608.txt （中文）can be downloaded via:
链接：https://pan.baidu.com/s/1dtOpslehkVYot7ck0Juzfg 
提取码：1111 


1.py   python程序

中文.txt  word2vec后的排好序的输出数据
英文.txt  ChemDataExtractor识别后的排好序的输出数据

Chinese.txt  中文原始语料库（万方+知网，2000-2021， 材料+化学, ~210,000 papers）
Sciences.txt 英文原始语料库（Sciencedirect，2000-2020， Materials, ~150,000 papers） 
stop_words.txt  停用词
userdict.txt   自定义词典


result.txt 英文预处理后语料库
result1.txt 中文预处理后语料库

0607.txt   英文分词后与photovoltaic最相关的3000个词（没用chemdataextractor）

word2vec0607.txt (English) and word2vec0608.txt （中文）

最后cosine排序完成的表格未保存

预测出的材料（需要DFT进一步模拟）：
中文(中文.txt)：硫属 CH3NH3PbX3 卤化物 CIS 钒酸盐  CuInS2  晶硅  MXenes Nb3Al TMDCs CuInS TMDs  硬炭  金属卤化物钙钛矿  GaSb  GaN  镓  AgMeO  ILs  硅烯  卟啉  含氧酸  AgSbSe2  InSb  CuNiSi  苯醌 硼烯 GaAs  **LiNixCoyAlzO2**   NiNb2O   Cos2

英文(英文.txt)：poly-Si,  ZnMnO2  a-SiH  NaSbS2  arsenide  BiPV?? copper-indium-gallium-selenide  silicon   BiHP   Aluminium  n-silicon  silicon  Titania LiyWO3 c-Si CdS  silicon  CuInGaSe2  Cu-Mn  MeOH   CdSCuInSe2   alpha-sexithiophen  CuSbSe2  PTB7-ThPC71BM FA4GeIISbIIICl12  poly3-hexylthiopheneindene-C60  hydrogen  LHP Perovskite PbPc  **LixMn2O4** (JVASP-7888)
 
混淆矩阵， Precision， Recall, F-score， Accuracy等数据（分词的准确率和Word2vec的准确率）需要进一步计算。



如果出现punkt问题：请下载下面文件并解压到代码提示的位置
链接: https://pan.baidu.com/s/1DBsHdDwcVrOa4odaB4TuKw 提取码: p5sj 复制这段内容后打开百度网盘手机App，操作更方便哦 
