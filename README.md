# Lattice Boltzmann Method
# 前言
近年来，将流体视为由大量粒子构成的离散体系，进而研究其统计学行为的介观方法备受关注。介观方法的不基于连续性假设，压力通过状态方程求解，天然并行等特性使得它成为了一个研究流体力学的潜在工具，事实上，如格子Boltzmann方法（Lattice Boltzmann method,以下简称，LBM），离散统一气体动力学方法（DUGKS）等方法已经吸引了众多研究者。LBM方法在诞生至今的三十年间，得到了长足的发展，被广泛运用于微/纳米尺度流，多相流，多孔介质流等众多领域。
本项目是记录自己在学习LBM过程中，通过网络搜集到的各种教材，Slides，目的是帮助“开荒”的初学者，快速形成对LBM的了解。    
  
# 一、中文著作      
中文讲LBM的书，据我所知，目前有4本，3本国内出版的，1本A.A.Mohamad的英文教材的中文译本。  
国内出版的三本教材分别是：
<<流体动力学的格子Boltzmann方法>>  
华中科大郭照立老师2002年出版的，因为封面是黄色的，而且是16开印刷的，所以我们戏称为“小~黄~书”，这本书应该是很早的对LBM方法进行系统整理的教材，
事实上也是郭老师本人在攻读博士学位期间所作的工作，所以这本书的部分内容是与郭老师的博士学位论文“模拟不可压流体流动的格子Boltzmann方法研究”重合的。

<<格子Boltzmann方法的原理及应用>>    
郭老师2008年出版的新书，这本书的话，将02年之后新发展的一些LBM模型，如FV-LBM,FE-LBM，离散速度LBM，并对LBM的应用方面进行了扩充，加上了多相流LBM方法，多孔介质LBM，微尺度流动的LBM方法等，这本书是很常见的入门推荐教材。  

<<格子Boltzmann方法的原理及应用>>    
2008年同年，西交大陶文铨院士的学生，何雅玲院士编写的教材出版，这也是一本经常被推荐的教材，书后有一个顶盖驱动空腔流的C++程序代码，应该是国内很多学生的启蒙代码了。    

<<格子玻尔兹曼方法 基础与工程应用 附计算机代码>>  
前面有“小黄书”，这本是“小红书”，是A.A.Mohamad在2011年出版的《Lattice Boltzmann Method Fundamentals and Engineering Applications with Computer Codes》的中文翻译版本，这本书写的比较浅显，更加基础，且每一个章节都有Fortran代码，网上有科研人员将Fortran代码用C++又重新写了一遍，供参考：[C++版Mohamad代码](https://github.com/zmhhaha/LBM-Cplusplus-A.A.Mohamad)  

# 二、英文著作      
在英文书籍方面，可以在LibGen上用关键词检索，我这里放几本重要的。
<<Lattice-gas cellular automata and lattice Boltzmann models>>
  作者：Wolf Gladrow，这本书可能是最早的LBM的书，出版于2000年。  
  
<<The Lattice Boltzmann Equation for Fluid Dynamics and Beyond>>  
对于LBM做出了开创性工作的Prof Sauro.Succi，这位大牛挺有意思，每一章节开始的时候都会放一句话，什么孔子，Bob Dylon，还挺有情怀的。  
  
 <<Lattice Boltzmann Modeling: An Introduction for Geoscientists and Engineers>>
这本书侧重多相流，比较薄，可以作为多相流入门的好教材。  
  
  <<Lattice Boltzmann Method and its Applications in Engineering>>
  2013年，郭照立老师和新加坡国立另一位大牛--Chang Shu老师合著的，郭老师的章节基本就是中文版本的翻译，增加了Immersed Boundary Method，即浸没边界法的部分，Chang Shu老师的部分是LBM在可压缩流动流域的应用。  
  
  <<>>
