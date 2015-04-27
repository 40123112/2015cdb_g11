# 由 scrum_2 組員所寫的考試報告
說明 Brython 協同繪圖模式下, 與 JavaScript canvas 繪圖對應的相關概念與可用指令

Brython的目標是用Python取代JavaScript，使Python成為web瀏覽器的腳本語言。
V:\2015cdb_g11\cp_project.leo,<?xml version="1.0" encoding="utf-8"?>
<!-- Created by Leo (http://webpages.charter.net/edreamleo/front.html) -->
<?xml-stylesheet ekr_test?>
<leo_file xmlns:leo="http://www.leo-editor.org/2011/leo" >
<leo_header file_format="2"/>
<vnodes>
<v t="amd.20150414195850.1"><vh>@edit scrum_1.md</vh></v>
</vnodes>
<tnodes>
<t tx="amd.20150414195850.1">@language md
# 說明 Brython 協同繪圖模式下, 與 JavaScript canvas 繪圖對應的相關概念與可用指令

Brython的目標是用Python取代JavaScript，使Python成為web瀏覽器的腳本語言。

使用方法(範例)
&lt; html &gt; 
&lt; head &gt; 
&lt; script  src = "/brython.js" &gt;&lt;/ script &gt; 
&lt;/ head &gt; 
&lt; body  onLoad = "brython()" &gt; 
&lt; script  type = "text/python" &gt;
def echo():
    alert(doc[ "zone" ].value)
 &lt;/ script &gt; 
&lt; input  id = "zone" &gt; &lt; button  onclick = "echo()" &gt; clic ! &lt;/ button &gt; 
&lt;/ body &gt; 
&lt;/ html &gt;

建立a link

link1 = A( 'Brython' , href= 'http://www.brython.info' )
link2 = A(B( 'Python' ), href= 'http://www.python.org' )

建立a 並附加屬性

link = A()
 link &lt;= B( 'connexion' )
 link .href = 'http://example.com'
 
AJAX

req = ajax()
req.on_complete = on_complete
req.set_timeout(timeout, err_msg)
req. open ( 'POST' , url, True)
req.set_header( 'content-type' , 'application/x-www-form-urlencoded' )
req. send (data)

Local storage

local _storage[ 'foo' ] = 'bar' 
log ( local _storage[ 'foo' ])
del local _storage[ 'foo' ]
 log ( local _storage[ 'foo' ]) # prints None

</t>
</tnodes>
</leo_file>

使用方法(範例)
< html > 
< head > 
< script  src = "/brython.js" ></ script > 
</ head > 
< body  onLoad = "brython()" > 
< script  type = "text/python" >
def echo():
    alert(doc[ "zone" ].value)
 </ script > 
< input  id = "zone" > < button  onclick = "echo()" > clic ! </ button > 
</ body > 
</ html >

建立a link

link1 = A( 'Brython' , href= 'http://www.brython.info' )
link2 = A(B( 'Python' ), href= 'http://www.python.org' )

建立a 並附加屬性

link = A()
 link <= B( 'connexion' )
 link .href = 'http://example.com'
 
AJAX

req = ajax()
req.on_complete = on_complete
req.set_timeout(timeout, err_msg)
req. open ( 'POST' , url, True)
req.set_header( 'content-type' , 'application/x-www-form-urlencoded' )
req. send (data)

Local storage

local _storage[ 'foo' ] = 'bar' 
log ( local _storage[ 'foo' ])
del local _storage[ 'foo' ]
 log ( local _storage[ 'foo' ]) # prints None

