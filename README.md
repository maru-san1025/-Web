<!DOCTYPE html>
<html lang="ja">
    <head>
        <meta charaset = "uf-8">
           <style>
            #parent{
                width:300px;
                height:300px;
                border: 1px solid blue;
                position: relative;
                margin: auto;
                
            }
            .child{                
                width: 100px;
                height: 100px;
                border: 1px solid red;
                background-image: url(7560a.png);
                background-size: 100%;
                            }
            .center{
                position:absolute;
                top: 0px;
                left: 0px;
                right: 0px;
                bottom: 0px;
                margin: auto;
            }    
            #parent{
                transform-style: preserve-3d;
                perspective: 300px;
            }
            #child1{
               animation: anime1 3s linear 0s infinite normal both;
            }
            @keyframes anime1{
                0%{rotate:y 0deg;}
                100%{rotate:y 360deg;}
            }
              
            
        </style>
        </head>
        <body>
            <div id="parent">![tokyo](https://github.com/user-attachments/assets/07ed7931-94c0-40ce-a0d0-230a1e5a9eec)

                <div class = "child center"
                id = "child1"></div>
             
            </div>
        </body>
</html>

