# 由 scrum_2 組員所寫的考試報告
說明 Brython 協同繪圖模式下, 與 JavaScript canvas 繪圖對應的相關概念與可用指令

Brython的目標是用Python取代JavaScript，使Python成為web瀏覽器的腳本語言。

使用方法(範例)
&lt; html &gt; <br>
&lt; head &gt; <br>
&lt; script  src = "/brython.js" &gt;&lt;/ script &gt; <br>
&lt;/ head &gt; <br>
&lt; body  onLoad = "brython()" &gt; <br>
&lt; script  type = "text/python" &gt;<br>
def echo():<br>
    alert(doc[ "zone" ].value)<br>
 &lt;/ script &gt; <br>
&lt; input  id = "zone" &gt; &lt; button  onclick = "echo()" &gt; clic ! &lt;/ button &gt; <br>
&lt;/ body &gt; <br>
&lt;/ html &gt;

建立a link

link1 = A( 'Brython' , href= 'http://www.brython.info' )<br>
link2 = A(B( 'Python' ), href= 'http://www.python.org' )

建立a 並附加屬性

link = A()<br>
 link &lt;= B( 'connexion' )<br>
 link .href = 'http://example.com'<br>
 
AJAX

req = ajax()<br>
req.on_complete = on_complete<br>
req.set_timeout(timeout, err_msg)<br>
req. open ( 'POST' , url, True)<br>
req.set_header( 'content-type' ,<br> 'application/x-www-form-urlencoded' )<br>
req. send (data)<br>

Local storage<br>

local _storage[ 'foo' ] = 'bar' <br>
log ( local _storage[ 'foo' ])<br>
del local _storage[ 'foo' ]<br>
 log ( local _storage[ 'foo' ]) # prints None


