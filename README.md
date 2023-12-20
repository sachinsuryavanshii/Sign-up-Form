# Sign-up-Form
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>


      <style>
            table
            {
                background-color: rgb(224, 174, 216);  
                margin-top: 2%;
                margin-bottom: 2%;
                margin-left: 35%;
                border: 2px solid rgb(0, 0, 0); 
                padding-top: 6%;
                padding-bottom:6%;
                padding-left: 3%;
                padding-right:3%;
            }
       </style>

</head>
<body>

    <form action="Login Form.html">
    
         <table>

            <tr>
                <td><h1>Sign Up Form</h1></td>
            </tr>


            <tr>
                <td>First Name :</td>
                <td><input type="text"placeholder="First Name" required></td>
            </tr>


            <tr>
                <td>Last Name :</td>
                <td><input type="text"placeholder="Last Name" required></td>
            </tr>

            <tr>
                <td>Email Id :</td>
                <td><input type="text"placeholder=" Email Id" required></td>
            </tr>

            <tr>
                <td>Phone Number :</td>
                <td><input type="text"placeholder="+91********" required></td>
            </tr>

            
            <tr>
                <td>Passward :</td>
                <td> <input type="password" placeholder="Passward" required></td>
            </tr>


            <tr>
                <td>Confirm Passward :</td>
                <td> <input type="password" placeholder="Confirm Passward" required></td>
            </tr>



            <tr>
                <!-- <td>Gender</td>
                <td><input type="radio" id="mgen" name="Gender">Male
                <input type="radio" id="fgen" name="Gender">Female</td> -->

               <td> <label for="mgen">Gender : </label> </td>
               <td>
                <input type="radio" id="mgen" name="gender" value="male" required/>
                <label for="mgen">Male</label> 
               
                <input type="radio" id="fgen" name="gender" value="female"required/>
                <label for="fgen">Female</label> 
                </td>
            </tr>


            <tr>
                <td>Date Of Birth :</td>
                <td><input type="date" name="Date Of Birth" id="dob" required></td>
            </tr>



            <tr>
                <td>Location :</td>

                <td> <input type="checkbox">Mumbai
                     <input type="checkbox">Pune
                     <input type="checkbox">Kolhapur
                </td>
            </tr>


            <tr>
                <td>Address :</td>
                <td>
                    <textarea name="Address" id="add" cols="28" rows="4" required></textarea>
                </td>
            </tr>



            <tr>
                <td>
                    <input type="submit" value="Submit" required>
                    <input type="reset" value="Reset" required>
                </td>
            </tr>


    
    </table>
    <!-- </fieldset> -->
   </form>
   
</body>
</html>
