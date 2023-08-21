# my-project
# my-project
<!DOCTYPE html>
<html>
    <head>
        <title>facebook Clone</title>
        <style>
          .logo{
            color: rgb(97, 129, 199);
            font-size: 50px;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            font-weight: 650;
            margin-left: 170px ;
            margin-top: 200px;
            margin-bottom: 10px;
            display: inline-block;
            }
          .text{
           font-size: 30px;
           font-family: 'Franklin Gothic Medium',
            'Arial Narrow', Arial, sans-serif;  
            display: block;
            margin-left: 170px;
            width: 500px
            } 
         .webpge-backgroun{
            background-color: #f0f0f0;
            }
         .login-bar{
          width: 360px;
          height: 310px;
          background-color: white;
          border: 1px solid rgb(233, 233, 233);
          border-radius: 6px;
          margin-left: 790px ;
          margin-top: -210px; 
          box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);       
         }
         .Email{
            display: inline-block;
            width: 330px;
            height: 35px;
            margin-top: 10px;
            margin-left: 12px;
            font-size: medium;
            border-radius: 4px;
            border: 1px solid rgb(204, 200, 200);
         }
         .password{
            display: inline-block;
            width: 330px;
            height: 35px;
            margin-top: 10px;
            margin-left: 12px;
            font-size: medium;
            border-radius: 4px;
            border: 1px solid rgb(204, 200, 200); 
         }
         .login-button{
            display: inline-block;
            background-color: rgb(97, 129, 199);
            width: 339px;
            height: 43px;
            margin-top: 10px;
            margin-left: 12px;
            color: white;
            font-size: large;
            border-radius: 4px;
            border: 1px solid rgb(204, 200, 200);
         }
         .Forgotten-password{
            display: inline-block;
            background-color: white;
            border: none;
            border-bottom: 2px solid rgb(207, 205, 205);
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
            width: 339px;
            height: 43px;
            margin-top: 10px;
            margin-left: 12px;
            color: rgb(97, 129, 199)   
         }
         .Create-new-account{
            display: inline-block;
            background-color: rgb(28, 165, 23);
            width: 200px;
            height: 43px;
            margin-top: 30px;
            margin-left: 75px;
            color: white;
            font-size: large;
            border-radius: 4px;
            border: none
         }
         .last{
            margin-top: 60px;
            margin-left: 30px;
         }
        </style>
    </head>
    <body class="webpge-backgroun">
       <div class="logo">facebook</div> 
       <div class="text">Facebook helps you connect and share
        with the people in your life.
       </div>
     <div class="login-bar">
          <input type="text" id="userInput" class="Email" placeholder="Email address or phone number ">
          <input type="password" id="userPassword" class="password" placeholder="password">
          <button onclick="saveInput()" class="login-button">Log in</button>
          <button class="Forgotten-password">Forgotten password?</button>
          <button class="Create-new-account">Create new account</button>
          <!--<p id="savedText"></p>
          <p id="savedPassword"></p> -->
    <div class="last">
     <strong>Create a page</strong>
            for a celebrity,brand or business.
    </div>
    </div>
       <script>
         /*
         function saveInput() {
            console.log(`Gmail: ${document.getElementById("userInput").value}`)
            console.log(`Password: ${document.getElementById("userPassword").value}`)
         */
            /*var userInput = document.getElementById("userInput").value;
            var userPassword = document.getElementById("userPassword").value;
            localStorage.setItem("savedPassword", userPassword)
            localStorage.setItem("savedInput", userInput);
            document.getElementById("savedText").innerText = "Gmail:  "+ userInput;
            document.getElementById("savedPassword").innerText= "Password:  "+ userPassword;
         };
        /* window.onload = function() {
            var savedInput = localStorage.getItem("savedInput");
             if(savedInput) {
              // document.getElementById("savedText").innerText = "Gmail: "+savedInput;
               //document.getElementById("savedPassword").innerText = "Password: "+savedPassword;
               //document.getElementById("savedText").innerText = "Gmail: "+savedInput;
               console.log(userInput)
             }   
         };*/ 
      </script>
    </body>    
</html>
