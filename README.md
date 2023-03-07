### you don't know my name, but you know my *past*
<br>
<p style="embed01">ayx / seven</p>
<p>i like scp, creepypasta, chills top15, and some other cringe things</p>
<p>stan trevor henderson 🛐🛐🛐</p>
<p>i suggest to listen to <a href="https://soundcloud.com/kmoethekid/wideeyes">kmoe - wide eyes</a></p>

FIGHT BACK YOUR TEARS WHEN YOU'RE CRYING, EMOTIONS SHOW IN YOUR **WIDE EYES**
<!--
**7valv/7valv** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.-->

/*this part is for styling it*/
<style>
#embed01 {
font-size: 1em;
font-family: arial;
filter: drop-shadow(1px 1px 0 black) drop-shadow(-1px 1px 0 black) drop-shadow(0 -1px 0 black) drop-shadow(1px 0 black);
}
</style>
<h2><script language="JavaScript1.2">
 
//Neon Lights Text II by G.P.F. (gpf@beta-cc.de)
//visit http://www.beta-cc.de
//Visit http://www.dynamicdrive.com for this script
 
var message="light-up"
var neonbasecolor="white"
var neontextcolor="#FFA4A4"
var neontextcolor2="#FF7E78"
var flashspeed=150 // speed of flashing in milliseconds
var flashingletters=3 // number of letters flashing in neontextcolor
var flashingletters2=1 // number of letters flashing in neontextcolor2 (0 to disable)
var flashpause=0 // the pause between flash-cycles in milliseconds
 
///No need to edit below this line/////
 
var n=0
if (document.all||document.getElementById){
document.write('<font color="'+neonbasecolor+'">')
for (m=0;m<message.length;m++)
document.write('<span id="neonlight'+m+'">'+message.charAt(m)+'</span>')
document.write('</font>')
}
else
document.write(message)
 
function crossref(number){
var crossobj=document.all? eval("document.all.neonlight"+number) : document.getElementById("neonlight"+number)
return crossobj
}
 
function neon(){
 
//Change all letters to base color
if (n==0){
for (m=0;m<message.length;m++)
crossref(m).style.color=neonbasecolor
}
 
//cycle through and change individual letters to neon color
crossref(n).style.color=neontextcolor
 
if (n>flashingletters-1) crossref(n-flashingletters).style.color=neontextcolor2
if (n>(flashingletters+flashingletters2)-1) crossref(n-flashingletters-flashingletters2).style.color=neonbasecolor
 
if (n<message.length-1)
n++
else{
n=0
clearInterval(flashing)
setTimeout("beginneon()",flashpause)
return
}
}
 
function beginneon(){
if (document.all||document.getElementById)
flashing=setInterval("neon()",flashspeed)
}
beginneon()
 
</script></h2>
