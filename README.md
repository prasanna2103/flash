<!DOCTYPE html>
<html>
    <style>
        .parent {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100%;
        }

        .container{
            width: 45%;
            height: 72%;
            padding: 10px;
            background-color: azure;
        }

    </style>
    <body>
        <head>
            <h1 style="text-align: center;"> JS basics</h1>
        </head>
        <div class="parent">
            <div class="container">
                <h2 style="font-size: medium; text-align: center; color: black;">add user</h2>
                <div style="display: flex; flex-direction: column;">
                    Name  <input type="text" id="name"><br>
                    Phone Number  <input type="text" id="phone number"><br>
                    <input type="submit" value="submit">
                </div>
            </div>
        </div>
    </body>
</html>
