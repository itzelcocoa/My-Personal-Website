# My-Personal-Website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=.5">
    <link rel="stylesheet" href="style.css">
    <link rel="shortcut icon" href="https://th.bing.com/th/id/OIP.VdGn9VRWMKR_5KkuuPHbzwAAAA?w=184&h=184&c=7&r=0&o=5&pid=1.7" type="image/x-icon">
    <title>My Personal Page</title>
    <style>
        body{
          background:#FEFFFF
        }
         @media (max-width:100px) {
         body{
           background:#FEFFFF
          }
         }
         @media (min-width: 1000px){
           body{
             background:#17232A
           }
         }

    </style>  
  
</head>

<body>
  
  <div class="wrapper">
    
  
    <div class="grid-container">
      <header class="grid-item header"><div class="container">
            <div class="hero-name">
                <div>
              <h1 class="main_title">Itzel Cocoa</h1>
                </div>
            </div>
             </header>
      <main class="grid-item main"> 
        <div class="hero-stmt">
                <div><p>Hello, my name is Itzel Cocoa I am a 22 year old from Arizona. I was born and raised in Tucson Az. cant really see myself living somewhere else. I really like hiking and playing mind games I like games that make you think. I am currently enrolled in correlation one studying software developing so far I am really liking it. Soon becoming a software engineer for Amazon or another big company. Something I really enjoy is being around family, I love the relationship I have with both sides of my family wouldn’t trade it for anything in the world. </p></div>
                    
            </div>
            </main>

      <aside class="grid-item aside-one">
        <ul class="menu_list">
        <li><a href="#">home</a></li>
        <li><a href="#">contact</a></li>
        </ul>
        </aside>   
        
      <aside class="grid-item aside-two">
        
        
        <img src="IMG_9525.jpg" style="width: 100px; height: auto" alt="">

      </aside>
      <footer class="grid-item footer"><div class="footer">
<div>
  <a href="https://www.linkedin.com/in/itzel-cocoa-2a2194166/"><img src="https://th.bing.com/th/id/OIP.PuMlA0fVGx8NPBXpX_T3JgHaHa?pid=ImgDet&rs=1" alt="linkedin" width="30" height="30" ></a>
  
  <a href="https://www.pinterest.com/itzelcocoa/"><img src="https://th.bing.com/th/id/OIP.p7aavUsv-85Zn8l-9ij9IgHaHa?pid=ImgDet&rs=1" alt="linkedin" width="30" height="30"></a>
</div>
       </footer>         
    </div>


    <div style="width: 50%; margin: auto; color: white; background-color: #white; padding: 10px; border-radius: -10px;">
    <form action="/submit_form" method="get">
<h2>Contact</h2>
        <label for="fname">First name?</label><br>
        <input type="text" id="fname" name="fname"><br>

        <label for="lname">Last name?</label><br>
        <input type="text" id="lname" name="lname"><br>

        <label for="mail">Email</label><br>
        <input type="email" id="mail" name="mail"><br>

        <label for="phone">Telephone number</label><br>
        <input type="number" id="phone" name="phone"><br>
        <input type="submit" value="Submit">

    </form>
</div>
</body>
</html> 
