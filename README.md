<!DOCTYPE html> 

<html lang="en"> 

  

<head> 

    <title> 

        Form validation using HTML 

        and JavaScript 

    </title> 

    <style> 

        div { 

            box-sizing: border-box; 

            width: 100%; 

            border: 100px solid black; 

            float: left; 

            align-content: center; 

            align-items: center; 
            
            text-color: black;
            
            background-color : lavendar;
        } 

  

        form { 

            margin: 0 auto; 

            width: 600px; 

        } 

    </style> 

</head> 

  

<body> 

    <h1 style="text-align: center;"> 

        REGISTRATION FORM 

    </h1> 

    <form name="RegForm" 

          onsubmit="return FORM()" netlify> 

        <p> 

            Name: 

            <input type="text" size="65" 

                   name="Name" required

                   /> 
        </p> 

        <br /> 


        <p> 

            E-mail ID: 

            <input type="text" size="65" 

                   name="EMail" required />         </p> 

        <br /> 

        <p> 

            Password: 

            <input type="password" size="65" 

                   name="Password"  requred/> 
        </p> 

        <br /> 
 <p> 

          Confirm Password: 

            <input type="password" size="65" 

                   name="Password"  requred/> 
        </p> 


        <br /> 

                   
        <p> 

            <input type="submit" value="Submit" 

                   name="Submit" /> 

            <input type="reset" value="Reset" 

                   name="Reset" /> 

        </p> 

    </form> 

    <script src="script1.js"></script> 

</body> 

  

</html>
