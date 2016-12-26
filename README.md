# JDK环境变量配置
   <p>1：下载jdk; 下载地址：<a href="http://pan.baidu.com/s/1gfDhXOf" rel="nofollow">http://pan.baidu.com/s/1gfDhXOf</a></p> 
<p>2：双击安装，安装jdk 随意选择目录 只需把默认安装目录 \java 之前的目录修改即可（最好默认C盘）；</p> 
<p>3：安装完JDK后配置环境变量 &nbsp;计算机→属性→高级系统设置→高级→环境变量</p> 
<p><img alt="" height="505" src="http://img.blog.csdn.net/20160619121046424?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQv/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center" width="563"></p> 
<p>4：系统变量→新建 JAVA_HOME 变量 。变量值填写jdk的安装目录（本人是C:\Program Files\Java\jdk1.8.0_45)</p> 
<p>5：系统变量→寻找 Path 变量→编辑，在变量值最后输入 %JAVA_HOME%\bin;%JAVA_HOME%\jre\bin;</p> 
<p>（本人是在其后面加；C:\Program Files\Java\jdk1.8.0_45\bin;C:\Program Files\Java\jdk1.8.0_45\jre\bin;）</p> 
<p>&nbsp;</p> 
<p>（注意原来Path的变量值末尾有没有;号，如果没有，先输入；号再输入上面的代码</p> 
<p><img alt="" height="179" src="http://img.blog.csdn.net/20160619121122732?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQv/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center" width="423"></p> 
<p>&nbsp;</p> 
<p>6：系统变量→新建 CLASSPATH 变量变量值填写 &nbsp; .;%JAVA_HOME%\lib;%JAVA_HOME%\lib\tools.jar（本人是.;C:\Program Files\Java\jdk1.8.0_45\lib;C:\Program Files\Java\jdk1.8.0_45\lib\tool.jar；&nbsp;注意最前面有一点）</p> 
<p>系统变量配置完毕</p> 
<p><img alt="" height="179" src="http://img.blog.csdn.net/20160619121200467?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQv/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center" width="423"></p> 
<p>&nbsp;</p> 
<p>最后检验是否配置成功 运行cmd 输入 java -version （java 和 -version 之间有空格）</p> 
<p>若如图所示 显示版本信息 则说明安装和配置成功。</p> 
<p><img alt="" height="88" src="http://img.blog.csdn.net/20160520155526947?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQv/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center" width="534"></p> 
<p>&nbsp;</p>
