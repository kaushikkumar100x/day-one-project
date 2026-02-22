# day-one-project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LOGIN form</title>
</head>
<body>
    <form action="">
        <div style="height: 300px; width: 600px; text-align: center; margin: auto;background-color: azure; margin-top: 220px;border-radius: 6%;">
           <header style="background-color: bisque;" > <h1><b>LOGIN FORM</b></h1>
            </header>
            <div>
                <label for=""><b>USERNAME :</b></label>
                <input type="text" id="username" name="username" placeholder="Enter the user name" required/>
                <br><br>
                <label for=""><b>PASSWORD :</b></label>
                <input type="password" maxlength="10" minlength="5" id="password" name="password" placeholder="Enter the password" required/>
                <br><br>
                <input type="checkbox">
                <label for=""><b>remembered Me :</b></label>
                <button value="submit" style="background-color: rgb(77, 77, 244);">LOGIN</button>
            </div>
    </form>
</body>
