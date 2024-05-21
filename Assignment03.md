<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <marquee behavior="slide" direction="up" scrollamount="20">
        <legend>
            <fieldset>
                <legend align="center">Registration</legend>
                <fieldset>
                        <legend align="center">Personal Info</legend>
                    Firstname: <input type="text" placeholder="Firstname">
                    lastname: <input type="text" placeholder="lastname">
                    Email: <input type="email" placeholder="pu.edu.np">
                    Phone: <select name="" id="">
                        <option value="">+977</option>
                        <option value="">+091</option> 
                        <option value="">+911</option>
                    </select>
                    <input type="number">
            
                    </fieldset>
        
                    <legend>
                        <fieldset>
                            <legend align="center">Ceredential</legend>
                            Username: <input type="text">
                            password: <input type="password">
                        </fieldset>
                    </legend> 
        
                    <legend>
                        <fieldset>
                            <legend align="Interest">Ceredential</legend>
                            Hobby: <input type="checkbox" checked>cricket
                                   <input type="checkbox">music
                                   <input type="checkbox">cricket
                                   <input type="checkbox">Football
                                <br>
        
                               
                        
                        </fieldset>
                    </legend> 
        
                    Faculty:<input type="checkbox" checked>IT
                    <input type="checkbox" >BCA
                    <input type="checkbox">Engineering
                    <br>
                    University: <input type="text" value="Pokhara University" readonly>
                    <br>
                    Photo: <input type="file" accept="image">
                    <br> 
                    Document: <input type="file" accept="Document">
                    <br>
                    Message:
                    <textarea name="" id="" rows="20" cols="20">type your message here</textarea>
                    <br>
                    <input type="submit">
                    <input type="reset">
                    <input type="button" value="Ok">
    </marquee>
</body>
</html>