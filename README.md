<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .container .item{
            background-color:rgb(153, 13, 13);
        }
        .footer-container .item{
         background-color: blue;
        }
        .main-container .item{
            background-color: green;
        }
        .botton{
            background-color: yellow;
            padding: 10xp;
        }
        .botton.active{
            background-color: orange;
            padding: 10xp;
        }
        .item1+.item2{
            background-color: yellowgreen;
        }
        input[type= "text"]{
            background-color: aquamarine;
       
        }
    </style>
</head>
<body>
    
    <div class="container">
        container
         <div calss ="item" >
            item
         </div>
    </div>

    <div class ="main-container">
           container

               <div class="item">
               item 1
               </div>
               <div class = "item">
               item 2
               </div>
               <div class = "item">
                item 3
               </div>
     </div>

            

    <button class = "botton">ปุ่ม</button>
    <button class = "botton active">ปุ่ม </button>
    <button class ="botton danger">ปุ่ม</button>

    <div class="item">item1 </div>
    <div class="item">item2 </div>
    <input type="text" name="username">
    <input type="text" password="password">
    <input type="text" email="email">




    </body>
</html>
