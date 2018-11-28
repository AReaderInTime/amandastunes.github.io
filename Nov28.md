# amandastunes.github.io
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Final for Independent Research</title>
        <style>
            #book-pic {
                border: 1px solid blue;
                width: 100px;
            }
            
            #book-text { 
                font-family: Monospace;
                color:rgb(17, 34, 222);
            } 
            body {
                background-color: rgb(179,179,179);
            }
            
            #genres {
                font-family: Monospace;
                color:rgb(102, 12, 102);
            }
            
        </style>
    </head>
    <body>
    
        <img id="book-pic" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ec/Record-Album-02.jpg/220px-Record-Album-02.jpg">
        
        <h1 id="book-text"> Music Library! </h1>
        
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.4/jquery.min.js"></script>
        
     <ul> 
         
         <li> <a href= "#songs-of-year"> View the Best Songs of 2018 </a>  </li> 
         <li> <a href = "#genres"> Browse Genres </a> </li> 
         <li> <a href = "#discover"> Discover New Music by Listening to Spotify Playlists</a> </li> 
     </ul>
     
     <h2 id = "songs-of-year"> Best Songs of 2018</h2>
     <ol> 
         <li> thank u next by Ariana Grande </li> 
         <li> The Middle by Maren Morris </li>
         <li> God's Plan by Drake </li> 
         <li> One Kiss by Dua Lipa </li> 
         <li> Better Now by Post Malone </li> 
         <li> Back to You by Selena Gomez </li> 
         <li> Natural by Imagine Dragons </li> 
         <li> God is a woman by Ariana Grande </li> 
         <li> Youngblood by 5 Seconds of Summer </li> 
         <li> 3:15 by Bazzi </li> 
         
     </ol>
     
       <h2 id = "genres"> Genres </h2> 
       
    <h3> <a href = "#classy"> Classical </a></h3>
    <h3><a href = "#country"> Country </a></h3>
    <h3><a href = "#electronic"> Electronic </a></h3>
<h3><a href = "#inde"> Indie / Alternative </a></h3>
    <h3><a href = "#jazz"> Jazz</a></h3>
    <h3><a href = "#kpop"> K - Pop</a></h3>
    <h3><a href = "#pop"> Pop </a></h3>
    <h3><a href = "#rb"> R & B </a></h3>
    <h3><a href = "#rock"> Rock </a></h3>
    <h3><a href = "#soul"> Soul / Blues </a></h3>
     
       <h2 id = "discover">  Playlists </h2>
        <p> Follow the links below to discover great music playlists for each genre.</p> 
        
         <h4> <a href = "https://www.youtube.com/watch?v=w3HCPVMtd8M"> Classical </a></h4>
        <h4> <a href = "https://www.youtube.com/watch?v=J2hkM6G1bDY">Country Music  </a></h4>
        <h4> <a href = "https://www.youtube.com/watch?v=ZYmTeUAOStA"> Electronic</a></h4>
        <h4> <a href = "https://www.youtube.com/watch?v=mmbroK0o2d0"> Indie / Alternative </a></h4>
        <h4> <a href = "https://www.youtube.com/watch?v=kUM7ZvE9deI"> Jazz </a></h4>
        <h4> <a href = "https://www.youtube.com/watch?v=6xinJn6LuxM"> K - Pop </a></h4>
        <h4> <a href = "https://www.youtube.com/watch?v=9UY6P75vMmA"> Pop </a></h4>
        <h4> <a href = "https://www.youtube.com/watch?v=MC6YLqio-bI&list=RDGMEMb2Vctm4zQjEID_BdYM0vuQ&start_radio=1"> R & B</a></h4>
        <h4> <a href = "https://www.youtube.com/watch?v=0I647GU3Jsc&list=PL3oW2tjiIxvQWubWyTI8PF80gV6Kpk6Rr">Rock </a></h4>
        <h4> <a href = "https://www.youtube.com/watch?v=sbDRos0P1xE"> Soul / Blues </a></h4>
        
        <h2 id="classy"> So Classy; All About Classical Music</h2>
        
       
        
     <img src = "https://www.kasandbox.org/programming-images/avatars/aqualine-ultimate.png"> 
<script src= "https://ajax.googleapis.com/ajax/libs/jquery/2.1.4/jquery.min.js"></script>  
        <script>
      
        $("#book-pic").animate ({
              width: "370px",
            marginLeft: "30px",
            borderWidth: "10px"
        }, 1500);
        
        $("#book-text").animate({
           marginLeft: "100px",
           fontSize: "3em"
        });
        
        $("#genres").animate({
           marginLeft: "100px",
           fontSize: "2em",
        });
        
    var $sound = $("<audio preload=auto>"); 
    $sound.attr("src", "https://cf-media.sndcdn.com/Bx3hR0UZi4Lh.128.mp3?Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiKjovL2NmLW1lZGlhLnNuZGNkbi5jb20vQngzaFIwVVppNExoLjEyOC5tcDMiLCJDb25kaXRpb24iOnsiRGF0ZUxlc3NUaGFuIjp7IkFXUzpFcG9jaFRpbWUiOjE1NDM0MzkwODB9fX1dfQ__&Signature=LzvIsa2x-Ykgyvnn2-Sd5N8g~fwS9TmsZKnjZQ0KqFP1bINUJnNAiW03a2xjFCdOF0xIqyTd6mTZtl6WtYdhJvXX8f8nqZUbmKtec4-0cOy2Ipb8xN7HmQ9Z1LQUa6CiL99iPrT2-07fuPhD8il-9xQ0ifGBTEKXFv~vcOYbVmlUa7s3Z3jhATiAw8jfZFwZOKyx7WBggVHvct7tlqyOe0guVIaZAE7QHesq8MyVPJH4UkWEjFizR2ujpcl367nGNt0E5V7txxHTYWmOFzhC6sQMiKVh6Pe17Db9eVzuUBIWsPbUP-RD6XrQLbUb4l5OLDbO08HndoRyHWVu5sRu0Q__&Key-Pair-Id=APKAJAGZ7VMH2PFPW6UQ"); 
    $("img").on("click", function() {
        $("body").append($sound);
        $sound[0].play();
    })
        
        </script> 
    
 
    </body>
</html>
