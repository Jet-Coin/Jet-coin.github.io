# Jet-coin.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>active learning</title>
    <meta http-equiv="refresh" content="100">
    <link href="trainning.css" rel="stylesheet">
</head>
<body>
    <div id="a1">
    

    </div><hr>

    <div id="a2">
        <!-- 2/2/2025-->
    Font style
    font strech
    font weight

    </div><hr>

    <div id="a3">
        <!-- 3/2/2025-->
    Boxes

    </div><hr>

    <div id="a4">
        <!--5/2/2025-->
  <ul id="a4">
    <li>table</li>
    <li>list</li>
    <li>forms</li>

  </ul> 
  <table class="a4">
    <thead>
        <tr>
            <th>Num</th>
            <th>priority</th>
            <th>profit"annaul"</th>
            <th>profit"monthly"</th>
        </tr>
       
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>important</td>
            <td>500$</td>
            <td>50$</td>
        </tr>
        <tr class="ch-color">
            <td colspan="2">2</td>
            <td>normal</td>
            <td>600$</td>
            <td>12$</td>
        </tr>
        <tr>
            <td>3</td>
            <td>normal</td>
            <td>1000$</td>
            <td>100$</td>
        </tr>
        <tr class="ch-color">

            <td >4</td>
            <td>low</td>
            <td>500$</td>
            <td></td>
        </tr>
    </tbody>
  </table> 

    </div><hr>

    <div id="a5">
    <!--5/2/2025-->
    <form action="" method="post">
        <p> complete this servey to get your licene</p>
    <fieldset>
    <legend>idintity</legend>
        <div class="form"><label  for="Name">Name </label><input type="text" name="" class="" id="Name" required></div>
        <div class="form"><label for="pass">password </label><input type="password" name="" id="pass" value="" class="" required></div>
        <div class="form"><label for="re-pass">re-enter password </label><input type="password" name="" id="re-pass" value="" class="" required></div>
        <div class="form"><input type="submit" name="sub" value="sign in" ></div>
    </fieldset>


    <fieldset>
        <legend></legend>
        <label></label>
    </fieldset>


    <fieldset>
        <legend></legend>
        <label></label>
    </fieldset>

    </form>
    </div><hr>
    <!-- 12/2/2025-->
    <div id="a6">
        <P class="float">i love my life</P>
        <div id="position">position this</div>
        <P class="float">i love my love</P>
    </div>

    <style>
    
    *{
    margin:40px 0;
    font-family:Verdana, Geneva, Tahoma, sans-serif;
    box-sizing: border-box;
    
}
/*
#a1{

}
*/
#a2::first-line{
    max-width:75%;
    text-indent: 10px;
    font-style: italic;
    font-stretch:normal;
    font-size: 20px;
    font-weight:bold;
    font-family: cursive,monospace,fantasy,sans-serif,serif;
    margin: 0 auto;
    text-transform: capitalize;
    text-decoration: overline;
    line-height: 15px;
    letter-spacing: 2px;
    word-spacing: 10px;
    text-align: justify;
    text-shadow: 2px 1px 5px rgb(203, 29, 29);
}
@font-face {
    font-family: "Jet";
    src: url();
}

#a3{
    margin: 0;
    width:100%;
    min-width:50px;
    max-width:500px;
    background-color: rgb(220, 194, 245);
    text-align:center;
    margin:  0px auto;
    border-style: ridge;
    border-left-color: aqua;
    display:block ;
    visibility: visible;
    border-radius: 10px;
    height:500px ;
    font-size: large;
    border-bottom-right-radius: 500px 250px;
    border-top-left-radius: 500px;
    border-image: url("image/bgimg.gif")  repeat;
    box-shadow: 0px 0px 1px 20px rgb(69, 52, 52);
    text-indent: -9999px;
 
}

#a4{
    margin: 0;
    list-style-type:disc;
    list-style-position: outside;
    list-style-image: url("image/bgimg.gif");
    list-style:desk outside url("image/bgimg.gif");

}
.a4{
    border:1px solid black;
    box-sizing: border-box;
    width: 100%;
    border-bottom: 5px solid black;
    border-top: 5px solid black;
    border-radius: 5px;
    background-color: rgb(160, 235, 153);
    empty-cells: hide;
    border-collapse:collapse;
    border-spacing: 1px;

}
th,td{
    padding:5px 10px;
    text-align: center;
    
}
th{
    background-color: bisque;
    font-weight: bold;
    text-transform: uppercase;
    border-bottom: 1px black solid;
    text-shadow: 3px 3px 7px rgb(113, 106, 106);
}
.ch-color{
    background-color: aquamarine;
    column-span: 2;

}

#a5 form{
    
    margin: 0 auto;
    max-width:500px;
    width:100%;
    border:solid 3px pink;
    border-radius: 5px;
}
label,input,p,fieldset{
    margin:0;

}
div .form{
    max-width:500px;
    width:100%;
    
    margin:20px auto;
    
    
}
label{
    
    text-align: left;
    margin-left:15%;
    width: 35%;
    

}
input{
    float: right;
    width:35%;
    margin-right: 15%;
    color: rgb(53, 42, 27);
    background-color: #eed95f;
    border: solid 1px #eed95f;
    border-radius: 5px;
    box-shadow: 3px 3px 5px 1px rgb(95, 91, 91);
    background: linear-gradient();
}


legend{
    text-transform: uppercase;
    border: solid 1px #eed95f;
    border-radius: 5px;
    background-color: #ead33c;
    padding:3px;
    margin:2px auto;
    max-width: 100px;
    width: 100%;
    text-align: center;
    color:rgb(71, 69, 69);
    box-shadow: 2px 2px 5px rgb(114, 105, 105);
    
}
input[type="submit"]{
    
    margin: 0 30%;
    background-color: bisque;
    border: solid 1px bisque;
    color: rgb(66, 66, 66);
    border-radius: 7px;
    box-shadow: 3px 3px 5px rgb(72, 71, 71);
    width:40%;

}
fieldset{
    border:solid 2px rgb(101, 97, 97);
    margin:5px;
    border-radius: 10px;
    
}
/** 12/2/2025**/
#a6{
   margin:20px auto;
   width:500px;
   max-width: 500px;
   border-radius: 10px;
   border:solid rgb(174, 115, 115) 2px; 
   overflow: scroll;
   height:200px;
}
.float,#position{
    border:1px black solid;
    margin:0px auto;
    width:400px;
    height:600%;
}
#position{
    border:solid 2px red;
    position: sticky;
    background-color: black;
    
}
    
    
    
    </style>
</body>
</html>
<html></html>

