<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="form.css">
    <title>Form</title>
</head>
<body>
    <div>
        <form action="#" method="post" class="form1">
           <h3> <b>Написать нам</b> </h3>
            <input type="text" name="text" placeholder="Username" ><br>
            <input type="email" name="email" placeholder="Email" ><br>
            <textarea name="area" id="" cols="20" rows="12" placeholder="   Сообщение...    " ></textarea><br>
            <input type="submit" value="Отправить" ><br>
        </form>
    </div>
    <div class="section2">
        <p class="appForm">Application Form</p>
        <form action="#" method="post" class="form2">
            <table>
                <tr>
                    <td> <label for="fname">First Name:</label></td>
                    <td><input type="text" name="fname" id="fname" placeholder="Utkir"><br></td>
                    <td><label for="fsurname">Last Name:</label></td>
                    <td><input type="text" name="fsurname" id="fsurname" placeholder="Begulov"><br></td>
                </tr>
                <tr>
                    <td> <label for="date">Date of birth:</label></td>
                    <td><input type="date" name="date" id="date" placeholder="mm/dd/yyyy"><br></td>
                    <td> <label for="age">Age:</label></td>
                    <td><input type="number" name="age" id="age" max="120" min="18" placeholder="number"><br></td>
                </tr>
                <tr>
                    <td><label for="gender">Gender:</label></td>
                    <td><select>
                        <option value="male" selected>Male</option>
                        <option value="fmale">Female</option>
                    </select><br></td>
                    <td> <label for="email">Email Address:</label></td>
                    <td><input type="email" name="email" id="email" placeholder="example@mail.com"><br></td>
                </tr>
                <tr>
                    <td colspan="4">
                        <label>Positions Available</label>
                        <input type="radio" name="position" id="first" checked>
                        <label for="first">Junior Developer</label>
                        <input type="radio" name="position" id="second">
                        <label for="second">Mid-level Developer</label>
                        <input type="radio" name="position" id="third">
                        <label for="third">Senior Developer</label><br>
                    </td>
                </tr>
                <tr>
                    <td colspan="4">
                        <label >Programming Language:</label>
                    <input type="checkbox" name="java" id="java" >
                    <label for="java">Java</label>
                    <input type="checkbox" name="javaScript" id="javaScript" >
                    <label for="javaScript">JavaScript</label>
                    <input type="checkbox" name="python" id="python" >
                    <label for="python">Python</label><br>
                    </td>
                </tr>
                <tr>
                    <td> <label for="pass">Password:</label></td>
                    <td> <input type="password" name="password" id="pass" placeholder="********"><br></td>
                    <td>  <label for="ConPass">Confirm Password:</label></td>
                    <td><input type="password" name="ConPass" id="ConPass" placeholder="********"><br></td>
                </tr>
                <tr>
                    <td colspan="2"><input type="submit" value="Submit" style="float: right;"></td>
                    <td colspan="2" style="float: left;"><input type="reset" value="Reset"></td>
                </tr>
            </table>
        </form>
    </div>
</body>
</html>
