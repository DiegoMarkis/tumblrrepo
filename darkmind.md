<html xmlns="http://www.w3.org/1999/xhtml">

<head>
<meta name="google-site-verification" content="0UqtQrF8j1G5V18KyKVClVjuoDgukB7PzkM3wDVZoQg" />
<meta name=”description” content="Welcome to my blog, I hope to help on your guest."/>
<meta name="keywords" content="diegomarkis,Diego Markis,Diegö Markis,tumblr">


 <title>{title}</title>
 <link rel="shortcut icon" href="{Favicon}"/>



  </head>
  


  <div class="cab">{title}</div>
        
  <style>

 html{width:700px;background-attachment:fixed;  background-image:url('http://i1332.photobucket.com/albums/w620/diecoms/wood-background-dark_zps31f1471e.jpg'); font-size:20px;background-color:transparent;text-align: ; margin-left:50px;}   

.cab{width:100%; height:240px;margin-left:25%; margin-bottom:-70px; font-size:400%;font-family:ShelleyVolante BT; float:left; color:#a7b7c9;
 /*background-image:url('http://address of your photo.png');*/
z-index:;float:left; background-repeat:no-repeat;}

body{background-color:; color:#666;float:right;text-align: center;}


.caption{background-color:transparent;margin-left:100px;margin-right:1px;width:98%;margin-top:0px;text-align: center;color:#b9b9b9;}

#postsvideo{background-color:#fc1;width:625px;height:auto;color:#333;float:left;border-style:;background-color:transparent; border-width:1px; border-color:#ccc;}
  
#posts{background-color:transparent; width:625px;color:#ddd;float:left;margin-left:35%; margin-left:35%; height:auto;text-align: center;border-style:solid;}
  
#frases{color:#555;position:center; background-color:transparent;border-style:;border-width:1px;float:left;width:100%; border-color:#ccc;}
   
#reblogui{background-color:transparent;}
   
#descricao{background-color:; width:625px; height:auto; float:left; clear:right; color:#111;margin-top:25px;margin-left:30%;float:left;}

#descricao a{color:#555;}

#descricao a:visited{color:;}

#descricao a:hover{color:#bbb;}


#pronext{color:#666;background-color:transparent;overflow:hidden;border-width:1px; border-color:#fff;}

#pronext a{text-decoration:none;color:#c9c9c9; display:inline;}

#pronext a:hover{text-decoration:overline;none;}

.reblogui{margin:0px;width:625px;}

a.reblogui{color:#40ff40; text-decoration:none; display:inline;margin:0px;
              }
a.reblogui:hover{color:#bbb; text-decoration:none;font-size:12px;display:inline;margin:0px;}

a.reblogui:visited{color:;}

a:hover{color:#111;}   
                                        
a{color:#c3c3c3; text-decoration:none;} 
 
a:visited{color:;} 
   
#direita a:hover{text-decoration:none;color:#ccc;opacity:1.5;}

#direita a{text-decoration:underline;color:#666;}
  
#direita{margin-left:70.5%; margin-right:auto;width:auto; margin-top:250px;
height:auto;color:#fff; position:fixed;/* 
background-image:url('http://i1332.photobucket.com/albums/w620/diecoms/fundo_zps1caca753.png');*/background-repeat: repeat; background-position:top right; float:left; overflow:hidden;}
  

#fotos{color:#333; width:150px;height:150px; float:left; clear:right; position:fixed;margin-top:200px;margin-left:3px; repeat:none;}

#foto{width:625px;height:auto;border-style:;border-width:1px;background-color:transparent;float:left; border-color:#222;}

#postphotoset{width:625px;height:auto;border-style:;border-width:1px;background-color:transparent;float:left; border-color:#222;}

#menu{float:left; color:#666;height:auto;}
#menu a {display: inline;}

hr{overflow:hidden;}

#notes{border-style:;border-width:1px;background-color:transparent;height:auto;font-size:12px;width:625px;  clear:right; border-color:#222;overflow:hidden;}

#notes li{display:inline-block;width:auto;list-style:none;margin:0px;padding: 1px 15px;float:left;overflow:hidden; 
}

#notes li a{color:#40ff40; text-decoration:none;}
#notes li a:hover{color:#d11; text-decoration:none;}
#postchat{background-color:transparent;width:auto;height:auto;float:left;}

#espaco{width:100%; height:10px;background-color:transparent;}
.caption{background-color:transparent; float:right;}




  </style>
 

   <body  style="margin:0px auto">
  

<center>
        <div id="descricao">{block:Description}
      <a class="seguir" title="Seguir" data-tumblelog-name="{name}" href="http://www.tumblr.com/follow/{name}">--{Description}</a><br />{/block:Description} </div> 
</center>


  <div id="fotos">{LinkOpenTag}<!--foto do lado-->
    <img src="{PortraitURL-128}" align="left" width="150px">{LinkCloseTag}
    <br />
  </div> 
        <div id="posts" style="background-color:transparent;">
            {block:Posts}
                {block:Text}
<!--frases-->      <div id="frases">
                        {block:Title}
                            <h3><a href="{Permalink}">{Title}</a></h3>
                        {/block:Title}

                        {Body}
                    </div>
                {/block:Text}
<!--foto--><div id ="espaco"></div>
                {block:Photo}<center>
                    <div id="foto">{LinkOpenTag} 
                 <img src="{PhotoURL-500}" alt="{PhotoAlt}"/>{LinkCloseTag}
                        {block:Caption}
                            <div class="caption">{Caption}</div>
                        {/block:Caption}
                    </div></center>
                {/block:Photo}
                
            <!--panorama-->
                {block:Panorama}
                    <div id="postpanorama">
                        {LinkOpenTag}
                            <img src="{PhotoURL-Panorama}" alt="{PhotoAlt}"/>
                        {LinkCloseTag}

                        {block:Caption}
                            <div class="caption">{Caption}</div>
                        {/block:Caption}
                    </div>
                {/block:Panorama}
<div id ="espaco"></div>
                {block:Photoset}
<!--photset-->                    <div id="postphotoset" align="center">
 <!--photset----> {LinkOpenTag}{Photoset-500}{LinkCloseTag}

                        {block:Caption}
                            <div class="caption"align="center" >{Caption}</div>
                        {/block:Caption}
                    </div>
                {/block:Photoset}<div id ="espaco"></div>
                
<!--citacao-->
                {block:Quote}
                    <div id ="frases" align="center">
                   <a href="{Permalink}">     "{Quote}"</a>

                        {block:Source}
                            <div class="source">{Source}</div>
                        {/block:Source}
                    </div>
                {/block:Quote}</p>
<!--link--><p>
                {block:Link}
                    <li class="post link">
                        <a href="{URL}" class="link" {Target}>{Name}</a>

                        {block:Description}
                            <div class="description">{Description}</div>
                        {/block:Description}
                    </li>
                {/block:Link}</p>
<p>
                {block:Chat}
                    <div id="postchat">
                        {block:Title}
                            <h3><a href="{Permalink}">{Title}</a></h3>
                        {/block:Title}</p>
<p><!--chat-->
                        <div id="chat">
                            {block:Lines}
                                <div id="{Alt} user_{UserNumber}">
                                    {block:Label}
                                        <span class="label">{Label}</span>
                                    {/block:Label}

                                    {Line}
                                </div>
                            {/block:Lines}
                        </div>
                    </div>
                {/block:Chat}</p>
<p><!--video-->
                {block:Video}
                    <div id="postsvideo" align="center">
                        {Video-500}<br/>

                        {block:Caption}
                           <div class="caption"align="center"> {Caption}</div>
                        {/block:Caption}
                    </div>
                {/block:Video}
</p><!--audio--><p>
                {block:Audio}
                    <li class="post audio">
                        {AudioPlayerBlack}

                        {block:Caption}
                            <div class="caption">{Caption}</div>
                        {/block:Caption}
                    </li>
                {/block:Audio}</p>
<p><div id="notes">
        <hr width="99%">
        <li>{block:PostNotes}{PostNotes-16}{/block:PostNotes}</li>
        <p><li>{ReblogButton}</li>
        <li>{LikeButton color="grey"}</li>
        <li><a href="{Permalink}">{NoteCountWithLabel}</a></li>
<li><a class="seguir" title="Seguir" data-tumblelog-name="{name}" href="http://www.tumblr.com/follow/{name}">--Seguir blog--</a></li>        
        


                <div id="reblogui">{DayOfMonth}/{MonthNumberWithZero}/{ShortYear}-{12Hour}:{Minutes}{AmPm}  
    <a href="{ReblogURL}" target="_blank" title="reblog" class="reblogui">    -Reblogar postagem acima.</a>  </div><hr width="99%"></p></div>
            
{/block:Posts}
            
            
<p>
 Desenhado por<a href="https://www.facebook.com/pages/Nightwish-Frases/237069239716537" target="_blank"> Nightwish Frases</a> 
 desenvolvido por <a href="http://diegomarkis.tumblr.com/" target="_blank">Diegö Markis</a>.         
</p>

</div>
       
<br />
   
<div id="direita">
  
  <div id="menu" align='center'>
  {block:PreviousPage}  <a href="{PreviousPage}"><< </a>{/block:PreviousPage}&nbsp
   <a href="/archive">Archive</a> &nbsp
   <a href="/ask">Ask me</a>&nbsp
   <a href="/">Home</a>{block:NextPage} <a href="{NextPage}">>></a>
 {/block:NextPage}
 <br />
   </div></div>	 


    </body>
</html>
