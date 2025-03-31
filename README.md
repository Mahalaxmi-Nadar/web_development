# web_development
DEVELOP A BASIC USER REGISTRATION AND LOGIN SYSTEM. USERS CAN REGISTER WITH THEIR EMAIL AND PASSWORD.

#login 

!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Page</title>
    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
            background-position:centre;
                background-repeat:no-repeat;
                background-size:cover;
            margin: 0;
            padding: 0;
        }

        .container {
            width: 300px;
            margin: 0 auto;
            margin-top: 100px;
            background-color: transparent;
            padding: 20px;
            box-shadow: 0 0 10px rgba(186, 9, 9, 0.2);
            border-radius: 5px;
        }
        .container h2 {
            text-align: center;
        }
        .form-group {
            margin-bottom: 15px;
        }
        .form-group label {
            display: block;
            margin-bottom: 5px;
        }
        .form-group input {
            width: 90%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 3px;
        }

        .form-group button {
            width: 100%;
            padding: 10px;
            background-color: #007BFF;
            color: #fff;
            border: none;
            border-radius: 3px;
            cursor: pointer;
        }
    .form-group button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body background="C:\Users\dell\Downloads\NEEDED2.jpg">
    <div class="container">
        <h2>Login</h2>
        <form>
            <div class="form-group">
                <label for="username">Username</label>
                <input type="text" id="username" placeholder="Enter username" required>
            </div><br>
            <div class="form-group">
                <label for="password">Password</label>
                <input type="password" id="password" placeholder="Enter password" required>
            </div><br>
            <div class="form-group">
                <button type="submit"><a href="file:///C:/Users/dell/Desktop/CONPRO.html#">Login</a></button>
            </div><br>
            <div class="link">
                Don't have an account?<a href="file:///C:/Users/dell/Desktop/SIGNUP.html"> Sign up</a>
            </div>
        </form>
    </div>
</body>
</html>

#SignupCode
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sign up page</title>
    <link rel="stylesheet" href="C:\Users\Mohit\Downloads\user login\style.css">
    </head>
    <body>
        <div class="container1">
            <h2>Sign up</h2><br>
            
            <form class="content">
                <div class="form-group1">
                    <label for="username">Username</label>
                    <input type="text" id="username" placeholder="Create username" required="">
                </div><br>
                <div class="form-group1">
                    <label for="password">Email</label>
                    <input type="email" id="email" placeholder="Enter Email" required="">
                </div><br>
                <div class="form-group1">
                    <label for="Create password">Password</label>
                    <input type="password" id="password" placeholder="Create password" required=""  minlength="8" pattern="^(?=.[A-Za-z])(?=.\d)(?=.[@$!%?&])[A-Za-z\d@$!%*?&]{8,}$">
                    <span class="lock-icon">🔒</span>  <small>Password must be at least 8 characters and contain at least one uppercase letter, one digit, and one special character </small>
                    
                </div><br>
                <div class="form-group1">
                    <label for=" password">Password</label>
                    <input type="password" id="Confirm password" placeholder="Confirm password" required="" minlength="8" pattern="^(?=.[A-Za-z])(?=.\d)(?=.[@$!%?&])[A-Za-z\d@$!%*?&]{8,}$ ">
                </div><br>
                <div class="form-group1">
                    <button type="submit"><a href="file:///C:/Users/dell/Desktop/PROJECT.html">Sign up</a></button>
                </div>
                </form>
            </div>  
</body>
</html>
<style>
body {
    font-family: Arial, Helvetica, sans-serif;
    background-position:centre;
        background-repeat:no-repeat;
        background-size:cover;
    margin: 0;
    padding: 0;
}

.container1 {
    width: 350px;
    margin: 425px;
    margin-top: 100px;
    background-color: transparent;
    padding: 30px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
    border-radius: 5px;
    height:600px;
    display:block;
}
.container1 h2 {
    text-align: center;
}

.form-group1 {
    margin-bottom: 15px;
}
.form-group1 label {
    display: block;
    margin-bottom: 5px;
}
.form-group1 input {
    width: 90%;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 3px;
}

.form-group1 button {
    width: 100%;
    padding: 10px;
    background-color: #007BFF;
    color: #fff;
    border: none;
    border-radius: 3px;
    cursor: pointer;
}
.form-group1 button:hover {
    background-color: #0056b3;
}
small{
    color:red
}
</style>
</head>
<body background="C:\Users\dell\Downloads\NEEDED2.jpg">

#next
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Simple Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        header {
            background-color: maroon;
            color: yellowgreen;
            text-align: center;
            padding: 10px;
        }
        nav {
            text-align: center;
        }
        nav a {
            text-decoration: none;
            margin: 10px;
            color: black;
        }
        section {
            margin: 20px;
        }
        footer {
            background-color: black;
            color: whitesmoke;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>SIMPLE DIMPLE</h1>
    </header>
    <nav>
        <a href="https://www.ruiacollege.edu/Department/Deptindex.aspx?page=a&ItemID=caeae&nDeptID=caaig">Home</a>
        <a href="https://www.ruiacollege.edu/Department/DisplayDeptPage.aspx?page=eci&ItemID=ego&nDeptID=caaig">About</a>
        <a href="https://www.ruiacollege.edu/Department/DisplayDeptPage.aspx?page=ecg&ItemID=egi&nDeptID=caaig">Contact</a>
    </nav>
    <section>
        <h2>About Us</h2>
        <p>The Group Members Of This Project Were <br>Soyebah Majeed<br>
            Harsh Nigam<br>
            Aryan Mishra<br>
            Suraj Salve<br>
            Soham Mane<br>
            Mahalaxmi Nadar<br>
            Grishma Maithania<br></p>
    </section>
    <section>
        <h2>Contact Us</h2>
        <p>You can reach us by calling or by whatsapp on this number "9323230105"</p>
    </section>
    <footer>
        &copy; GROUP 4 PROJECT ON TOP
    </footer>
</body>
</html>


