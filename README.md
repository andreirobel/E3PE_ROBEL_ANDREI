# E3PE_ROBEL_ANDREI
1.	How would you say that front-end development has evolved over the years? State some key difference from then (like 10 years ago) to now. 

-	The frontend needs to drive this transformation. The frontend cannot retreat from or bypass this task. Eventually, what is learned from web browser development can be used by front-end developers to craft code for environments that are not fueled by a browser engine. As of late, development environments are being dreamed up that use web technologies (e.g., CSS and JavaScript), without web engines, to create native applications. Netscape, Opera, and Internet Explorer were the most popular browsers at the time of front-end development. Owing to a shortage of equipment and techniques to work with, layout was put on the second plan. Since JavaScript and CSS did not exist at the time, front-end developers were tasked with fixing browser bugs and building tables to give content a more detailed appeal. To make the preferred templates and images properly, front-end developers had to adhere to a set of browser requirements. Performance problems were not given much thought, and cross-browser compatibility was given little weight. A front end developer's main task became to build pixel-perfect CSS and HTML based on carefully cut PSDs when Adobe Photoshop was proudly proclaimed as the revolutionary design tool in 1990 and CSS1 arrived six years later. The quality of HTML/CSS was primarily determined by how well it reproduced a given template. On the front-end side, there was no real "growth" going on. The web was a series of documents that were connected together, similar to how print media worked.

2.	Provide a code snippet that shows CSS precedence between element selectors, class selectors and inline styling.

<html>
<head>
    <style>
        body {
            font-family: Arial;
            font-size: 14px;
        }
        .pogi {
            font-family: Helvetica;
            font-size: 20px;
        }

    </style>
</head>
    
<body>
  <div id="header">
    <span class="pogi">Andrei</span>    
  </div>

  <div id="body">
   <p style="color:blue; font-size:22px;">
      Ang Katawan
    </p>
  </div>
</body>
</html>
