<!DOCTYPE html>
<html>
    <head>
        <title>Register</title>
    </head> 
    <body>
        <form>
            First name: <input type="text" name="firstname" required><br>
            Last name: <input type="text" name="lastname" required><br>
            Email: <input type="email" name="email"><br>
            Password: <input type="password" name="password" min="5"><br>
            Birthday: <input type="date" name="birthday"><br>
            Gender: <br>
            <input type="radio" name="gender" value="male">Male<br>
            <input type="radio" name="gender" value="female">Female<br>
            <input type="radio" name="gender" value="other">Other<br>
            Pets: <br>
            <input type="checkbox" name="cats">Cats<br>
            <input type="checkbox" name="dogs">Dogs<br>
            Cars: <br>
            <select name="cars">
                <option value="volvo">Volvo</option>
                <option value="Infini">Infini</option>
            </select><br>
            <input type="submit" value="Register Now">
            <input type="reset">
        </form>
    </body>   
</html>

?firstname=deus
&lastname=san
&email=deus%40gmail.com
&password=123
&birthday=2022-07-05
&gender=on
&cats=on
