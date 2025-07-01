
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>chandru's web page</title>
</head>
<body>
    <!-- This <div> tag is used as a container to group related HTML elements together.
     It helps in structuring the layout of the web page and can be styled using CSS.
     Common uses include sections like header, footer, sidebar, content area, etc. -->

    <div style="background-color:rgba(1, 9, 5, 0.455) ;height: 50px;">
<ul style="display: flex;list-style: none;padding-left: 10px;">
  <li class="name"   style="color: rgb(37, 146, 88);font-family: cursive;font-size: x-large;">CHANDRU.K</li> 
    <li>HOME</li>
    <li>HELP</li>
    <li>CONTACT US</li>
</ul> 
  </div>
  <!-- This <div> uses a class attribute to apply specific CSS styles or JavaScript behaviors.
     The class name can be reused on multiple elements for consistent styling or functionality.
     Useful for layout design, theming, or component-based structuring. -->

  <div class="imge">
    <img src="my img.png">

  </div>
  <div class="table">
    <table>
        <tr>
            <td>Name</td>
            <td>CHANDRU K</td>
        </tr>
        <tr>
            <td>Qualification</td>
            <td>B.Tech-IT</td>
        </tr>
        </tr>
            <td>Using Tools</td>
            <td>HTML,CSS,JAVASCRIPT</td>
        </tr>
        </tr>
            <td>Job Roll</td>
            <td>Fullstack-developer</td>
        </tr>
    </table>

  </div>
  <div class="logo">
    <ul style="display: flex;list-style: none;padding-left: 10px;">
        <!-- this <a> anger tag is used to isert a hyper link insaid the web page in this tag we need to write link in href-->
        <li><a href="https://github.com/chandru8428/README.MD"><img src="git.png" alt="github"></a></li> 
        <li><a href="https://www.linkedin.com/in/chandru-k2006?"><img src="link.png" alt="linkedin"></a></li> 
        <!-- this <img> tag is used to insert a image in the wbpage we need to write a link or location or name of the image in src-->
      </ul> 
  </div>
</body>
<!-- the style tag is used to insert css in web page the css of web page is insaid in the style tag-->
<style>
    ul li {
        padding-left: 30px;
        font-size: large;
        padding-top: 10px;
    }
    .name{
        padding-right: 500px;
    }
    .imge img {
        width: 200px;
        height: 200px;
        padding-left: 400px;
        padding-top: 100px;
    }
    .table{
        margin-left: 370px;
        margin-right: 360px;
        border-radius: 10px;
        border-style: groove;
        border-width: 3px;
        border-color: black;
        
    }
 .table tr td{
        border-color: black;
        border-width: 2px;
        border-style: groove;
    }
    .logo{
        margin-left: 400px;
    }
</style>
</html>

