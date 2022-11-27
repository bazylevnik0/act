Simple engine for visualizating collisions<br>
In console:<br> 
We can set start position, and speed/direction of elements(a,b)<br>
We can set collision mode(non-ellastic, ellastic)<br>
Then start and see)<br>
<hr>
Few examples:<br>
1) From diagonal corners to diagonal corners<br>
<b>set_el(a,0,0 ,[ 5,5])</b><br>
<b>set_el(b,800,800,[ -5,-5])</b><br>
<b>set_mode("ellastic")</b><br>
<b>start()</b><br>
2) From contr side but to one direction<br>
<b>set_el(a,0,400 ,[ 10,0])</b><br>
<b>set_el(b,800,400 ,[ -5,0])</b><br>
<b>set_mode("non-ellastic")</b><br>
<b>start()</b><br>
3) It's your turn... Contribute Welcome!


