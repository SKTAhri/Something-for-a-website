<!DOCTYPE html>
<html>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<head>
    <h1 style="text-align:center;">My Website</h1>
    <img src="https://imgur.com/35lR0kd.jpg" class="center" style="width:500px; height:300px;">

    <style>
    .center {
      display: block;
      margin-left: auto;
      margin-right: auto;
      width: 50%;
    }
    </style>
    
  <style>
    body { 
    background-color: cornsilk;
    }
    </style>

<style>
        h3 { 
          color:#800;
        }
        body {
          color:#800;
        }
        
        h1 {
          color:#800;
        }
        </style>

    <title>MyNewWebsite</title>
</head>
<body>

        <div class="w3-sidebar w3-bar-block w3-collapse w3-card w3-animate-right w3-brown" style="width:200px;right:0;" id="mySidebar">
                <button class="w3-bar-item w3-button w3-large w3-hide-large" onclick="w3_close()">Close &times;</button>
                <a href="#" class="w3-bar-item w3-button">Link 1</a>
                <a href="#" class="w3-bar-item w3-button">Link 2</a>
                <p><a href="https://github.com/SKTAhri/">MyGithub</a></p>
               <p><a href="https://www.youtube.com/channel/UCs5IRu5I6mR39AuGLyNbcWQ?view_as=subscriber/">My Youtube</a></p>
                <a href="file:///C:/Users/joshf/OneDrive/Documents/Website/Javascript.html">MyOtherWebsite</a>
              </div>

              <div id="content">
              <div id="nav">
              <h3>Navigation</h3>
              <li>Home</li>
              <li>About</li>
              <li>Contact</li>
                
             

            
      <div id="clockbox" style="text-align:center;"></div>

       <script type="text/javascript">
        function GetClock(){
        var d=new Date();
        var nmonth=d.getMonth(),ndate=d.getDate(),nyear=d.getFullYear();
        var nhour=d.getHours(),nmin=d.getMinutes(),nsec=d.getSeconds(),ap;
        
        if(nhour==0){ap=" AM";nhour=12;}
        else if(nhour<12){ap=" AM";}
        else if(nhour==12){ap=" PM";}
        else if(nhour>12){ap=" PM";nhour-=12;}
        
        if(nmin<=9) nmin="0"+nmin;
        if(nsec<=9) nsec="0"+nsec;
        
        var clocktext=""+(nmonth+1)+"-"+ndate+"-"+nyear+" "+nhour+":"+nmin+":"+nsec+ap+"";
        document.getElementById('clockbox').innerHTML=clocktext;
        }
        
        GetClock();
        setInterval(GetClock,1000);
        </script>

        



        <h1 style="text-align:center;">欢迎来到我的共产党网站</h1>
        <p style="text-align:center;">ㅇ쇼호ㅙ츄</p>
        <p style="text-align:center;">Perkele</p>
        
        
        <style> 
.div2 {
  margin:auto;
  width: 800px;
  height: 500px;  
  padding: 50px;
  border: 5px solid #800;
}
</style>




<br>
<div class="div2">This div is bigger (width is also 300px and height is 100px).
 <img class="w3-round-large" src="https://imgur.com/X78RL6G.jpg" style="width:50%">
</div>

<style>
.div3 {
  margin:auto;
  width: 800px;
  height: 5px;  
  padding: 50px;
  border: 5px solid #800;
  
}
</style>
<br>
<div class="div3">
 <div style="text-align:center;">AUF DER HEIDEN, Wilkommen to meine seltsam website.</div>
    
</div>
   
   
   <table class="div3">
     <tr>
      <th>Team Name</th>
      <th>Date Joined</th>
      <th>League</th>
     </tr>
     <tr>
      <td><a href="https://lol.gamepedia.com/SK_Telecom_T1">SKT T1</a></td>
      <td>2014-02-15</td>
       <td>LCK</td>
      </tr>
      <tr>
        <td><a href="https://lol.gamepedia.com/FunPlus_Phoenix">FunPlus Phoenix</a></td>
        <td>2017-12-20</td>
        <td>LPL</td>
      </tr>
      <tr>
        <td><a href="https://lol.gamepedia.com/Team_Liquid">Team Liquid</a></td>
        <td>2015-01-06</td>
        <td>NALCS</td>
      </tr>

   </table>

   </div>
   <div style="text-align:center;">Very much a work in progress</div>
   Copyright &copy; Mikko
  
          
        
          
          

              

</body>
</html>
