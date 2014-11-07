###  CDN公共库地址

Google 
主页 https://developers.google.com/speed/libraries/?hl=zh-CN
<script src="//ajax.googleapis.com/ajax/libs/jquery/1.8.1/jquery.min.js"></script>

Microsoft
主页  http://www.asp.net/ajax/cdn#jQuery_Releases_on_the_CDN_0
<script src="http://ajax.aspnetcdn.com/ajax/jQuery/jquery-1.8.1.js"></script>
<script src="http://ajax.aspnetcdn.com/ajax/jQuery/jquery-1.8.1.min.js"></script>

BaiDu
主页：http://developer.baidu.com/wiki/index.php?title=docs/cplat/libs

<script src="http://libs.baidu.com/jquery/1.9.0/jquery.js"></script>

奇虎360
主页：http://libs.useso.com/

JQuery.com
主页 http://code.jquery.com/ui/

http://code.jquery.com/mobile/

Bootcss
http://open.bootcss.com/

Sina
主页 http://sae.sina.com.cn/doc/php/cdn.html

http://lib.sinaapp.com/

防止加载失败方案：

<script src="http://libs.baidu.com/jquery/1.9.0/jquery.min.js"></script>
<script type="text/javascript">  <!--  !window.jQuery && document.write('<script src=/jQuery/jquery-1.9.0.min.js><\/script>'); //-->  </script>

 
也可以这样 

<!--  document.write(unescape("%3Cscript src='http://libs.baidu.com/jquery/1.9.0/jquery.min.js' type='text/javascript'%3E%3C/script%3E")); !window.jQuery && document.write(unescape("%3Cscript src='/jQuery/jquery-1.9.0.min.js' type='text/javascript'%3E%3C/script%3E")); //--> 