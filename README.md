# 搭建Eclipse+ADT+Android SDK 安卓开发环境
<h1>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 搭建Eclipse+ADT+Android SDK 安卓开发环境</h1> 
<span id="OSC_h3_2"></span>
<h3>安装JDK</h3> 
<p>请看<a href="https://my.oschina.net/zhangqie/blog/778364" rel="nofollow">JDK环境搭建</a>&nbsp;即可。</p> 
<p>&nbsp;</p> 
<span id="OSC_h3_3"></span>
<h3>安装Eclipse</h3> 
<p>Eclipse 是一个开放源代码的、基于Java的可扩展开发平台。就其本身而言，它只是一个框架和一组服务，用于通过插件组件构建开发环境。幸运的是，Eclipse 附带了一个标准的插件集，包括Java开发工具（Java Development Kit，JDK）。我们可以通过在Eclipse中添加ADT(Android Development Tools)安卓开发工具，来搭建安卓开发环境。</p> 
<span id="OSC_h4_4"></span>
<h4>下载Eclipse</h4> 
<p>下载地址:<a href="http://www.eclipse.org/downloads/" target="_blank" rel="nofollow">http://www.eclipse.org/downloads/</a>&nbsp; &nbsp;根据个人喜欢下载即可</p> 
<p>下载完毕后，你会在你保存的地方看到一个压缩包文件，这就是eclipse，直接解压缩即可。解压完毕后即可使用，进入文件夹，双击Eclipse图标后，就可以启动Eclipse了,到这Eclipse就安装完毕了。接下来是到Android开发者网站上去下载ADT 工具和android sdk文件。</p> 
<p>ADT下载：<a href="http://pan.baidu.com/s/1gfG5NDh" target="_blank" rel="nofollow">http://pan.baidu.com/s/1gfG5NDh</a>&nbsp;&nbsp; 密码：gtte</p> 
<p>SDK下载：<a href="http://sdk.android-studio.org/" target="_blank" rel="nofollow">http://sdk.android-studio.org/</a>&nbsp; &nbsp;根据个人需要下载对应版本即可</p> 
<p>&nbsp;</p> 
<p>eclipse安装ADT</p> 
<p>&nbsp;</p> 
<ul> 
 <li>1.下载ADT插件的zip文件（不要解压）</li> 
 <li>2.启动Eclipse,然后在菜单栏上选择 Help &gt; Install New Software</li> 
 <li>3.单击 Add 按钮，在右上角，</li> 
 <li>4.在"Add Repository"对话框，单击"Archive"</li> 
 <li>5.选择下载的adt-23.0.6.zip文件并单击"确认"。</li> 
 <li>6.在Name(名称)处输入"ADT",单击“Finish”</li> 
 <li>7.在软件对话框中,选中"Developer Tools"复选框,然后点击"Next"</li> 
 <li>8.在下一个窗口中，您会看到一个要下载的工具列表。单击“Next”</li> 
 <li>9.阅读并接受许可协议，然后单击“Finish”</li> 
 <li>10.安装完成后，重新启动Eclipse</li> 
</ul> 
<p>eclipse安装SDK</p> 
<ul> 
 <li>1.启动Eclipse,选择windows&gt;preferences&gt;android</li> 
 <li>2.在选项卡中选择"Browse",选择之前下载的Android SDK的zip文件(需要解压)的目录(解压后的目录),点击确定</li> 
 <li>3.点击OK&nbsp;</li> 
</ul> 
<p>如图：</p> 
<p>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<img alt="" height="623" src="https://static.oschina.net/uploads/space/2016/1031/114520_9NWn_2945455.png" width="705"></p> 
<span id="OSC_h3_5"></span>
<h3>通过Android SDK Manage添加新的软件包</h3> 
<ul> 
 <li>1.启动Eclipse,在菜单栏上点击<img alt="技术分享" height="28" src="https://static.oschina.net/uploads/img/201610/31115424_jqMG.png" width="24"></li> 
 <li>2.运行后出现如下界面，选择自己需要的Android版本，然后点击"Install X packages"。Installed 表示已经安装、Not installed表示没有安装!!</li> 
</ul> 
<p><img alt="" height="463" src="https://static.oschina.net/uploads/space/2016/1031/114750_M6IK_2945455.png" width="573"></p> 
<ul> 
 <li>3.在新出现的界面中选择如下Accept或者Accept All,然后点击Install。Android SDK 管理器就开始下载并安装你所选的包了，等一段时间就OK了！</li> 
</ul> 
<p><img alt="" height="367" src="https://static.oschina.net/uploads/space/2016/1031/114840_G21o_2945455.png" width="598"></p> 
<p><img alt="" height="418" src="https://static.oschina.net/uploads/space/2016/1031/114857_8IFg_2945455.png" width="587"></p> 
<span id="OSC_h3_6"></span>
<h3>AVD Manage创建安卓虚拟机</h3> 
<ul> 
 <li>1.启动Eclipse,在菜单栏上点击<img alt="技术分享" height="26" src="https://static.oschina.net/uploads/img/201610/31115424_2stD.png" width="22"></li> 
</ul> 
<p><img alt="" height="514" src="https://static.oschina.net/uploads/space/2016/1031/114949_EX1N_2945455.png" width="800"></p> 
<ul> 
 <li>2.点击Create按钮，进行如下设置，然后点击"OK"</li> 
</ul> 
<p><img alt="" height="752" src="https://static.oschina.net/uploads/space/2016/1031/115027_7uPl_2945455.png" width="539"></p> 
<ul> 
 <li>3.选中刚才创建的虚拟设备,然后点击“Start-&gt;Launch”，就可以启动 Android 模拟器了。</li> 
 <li>这样就可以创建项目，开发并运行了。<span style="color:#FF0000">不想用Android自带模拟器也可下载第三方的来使用，如夜深，海马等。</span></li> 
</ul> 
<p>&nbsp;</p>
