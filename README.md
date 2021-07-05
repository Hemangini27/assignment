# assignment
UI assignment
<html>
    <head>
        <title>Assignment</title>
        <style>
           #div1{position: absolute;
             width: 1529px;
             height: 645px;
             left: 0px;
             top: 72px;

            background: rgba(218, 210, 210, 0.3);
            }
            #text-Videos{
                position: absolute;
                width: 63px;
                height: 23px;
                left: 190px;
                top: 25px;

                font-family: Roboto;
                font-style: normal;
                font-weight: bold;
                font-size: 16px;
                line-height: 23px;

                color: #ADADAD;

            }
            #text-or{
                position: absolute;
                width: 63px;
                height: 23px;
                left: 800px;
                top: 150px;

                font-family: Roboto;
                font-style: normal;
                font-weight: bold;
                font-size: 16px;
                line-height: 23px;

                color: black;

            }

            
           #box-shadow{position: absolute;
          width: 143px;
          height: 725px;
          left: 0px;
           top: 0px;

          background: #FFFFFF;
          box-shadow: 10px 0px 20px rgba(0, 0, 0, 0.2);
            
           }
           #line-border{position: absolute;
              width: 139px;
             height: 0px;
             left: 0px;
             top: 72px;
             background: #E3DADA;
             border: 2px solid #E3DADA;
             transform: rotate(180deg); 

            }
            #insert-URL{position: absolute;
             width: 935px;
             height: 35px;
             left: 355px;
             top: 100px;

             background: #FFFFFF;
             border-radius: 22px;
             border:2px solid white;

            }
           input::placeholder{
                font-style: bold;
            }
            #rectangle{
                position: absolute;
                width: 120px;
                height: 120px;
                left: 358px;
                top: 220px;

                background: #FFFFFF;
            }
            #text-upload{
                position: absolute;
                width: 62px;
                height: 23px;
                left: 40px;
                top: 40px;

                font-family: arial;
                font-style: normal;
                font-weight: bold;
                font-size: 10px;
                line-height: 23px;

                color: #000000;

             }
            #image{
                position: absolute;
                width: 40px;
                height: 40px;
                left: 41px;
                top: 103px;
            } 
            #student{
                position: absolute;
                width: 63px;
                height: 23px;
                left: 35px;
                top: 132px;

                font-family: Roboto;
                font-style: normal;
                font-weight: bold;
                font-size: 14px;
                line-height: 23px;

                color: #ADADAD;

            }
            #image1{
                position: absolute;
                width: 40px;
                height: 40px;
                left: 41px;
                top: 200px;
            }
            #lesson-plan{
                position: absolute;
                width: 63px;
                height: 23px;
                left: 35px;
                top: 230px;

                font-family: Roboto;
                font-style: normal;
                font-weight: bold;
                font-size: 14px;
                line-height: 23px;

                color: black;

            }
            #image2{
                position: absolute;
                width: 40px;
                height: 40px;
                left: 41px;
                top: 310px;}
            #setting{
                position: absolute;
                width: 63px;
                height: 23px;
                left: 35px;
                top: 340px;

                font-family: Roboto;
                font-style: normal;
                font-weight: bold;
                font-size: 14px;
                line-height: 23px;

                color: #ADADAD;

            }
            #line2{position: absolute;
                width: 40px;
                height: 0px;
                left: 0px;
                top: 230px;
                background: #2B519A;
                border: 2px solid #2B519A;
                transform: rotate(90deg);
            }
            #image3{
                position: absolute;
                width: 40px;
                height: 40px;
                left: 41px;
                top: 20px;
            }
            #light-box{
                position: absolute;
                width: 143px;
                height: 110px;
                left: 0px;
                top: 180px;

                background: rgba(43, 81, 154, 0.3);
            }
        </style>
    </head>
    <body >
        <div id="box-shadow">
            <div id="line-border"></div>
        </div>
     <div id="div1">
           <div> <input type="text" id="insert-URL" placeholder="Insert URL here">
            </div>
            <div><p id="text-videos">Videos</p></div>
            <div><p id="text-or">or</p></div>
                <div id="rectangle"><p id="text-upload">upload</p></div>
           
     
            </div>
            <div id="box-shadow">
                <div id="line-border"></div><div id="line2"></div>
                <img src="data:image/png;base64,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" id="image3">
                <img src="data:image/png;base64,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" id="image">
             <p id="student">students</p>
              <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ1GuUDEePC5MOGp-TZmuIz1A8poQTkyafKyg&usqp=CAU" id="image1">
              <p id="lesson-plan">Lesson plan</p>
              <img src="data:image/png;base64,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" id="image2">
              <p id="setting">settings</p>
              <div id="light-box"></div>
            </div>

        </div>
    </body>
</html>
