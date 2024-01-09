<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration</title>
    <link rel="icon" type="image/x-icon" href="pictures/YT.jpg">
    <style>
        body{
            background-color: skyblue;
            margin: 70px;
        }
        .main{
            color: darkred;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        .calling{
            color: black;
            font-family: Georgia, 'Times New Roman', Times, serif;
        }
    </style>
</head>
<body>
    <div>
        <h1 class="main">Car Registration</h1>
        <h3 class="calling">Name and Adress:</h3>
    </div>
    <div>
        <form>
                <label for="fname">First Name</label><br>
                <input type="text" id="fname" name="fname" placeholder="First Name"><br><br>
                <label for="lname">Last Name</label><br>
                <input type="text" id="lname" name="lname" placeholder="Last Name"><br><br>
                <label for="date">Birth Date</label><br>
                <input type="date" id="date" name="birth date"><br><br>
                <label for="file">Passport</label><br>
                <input type="file" id="file" name="passport"><br><br>
                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email" placeholder="email@gmail.com"><br><br>
                <label for="phone">Telephone</label><br>
                <input list="code" name="country code" size="3" placeholder="code">
                <datalist id="code">
                    <option value="+250">+250</option>
                    <option value="+256">+256</option>
                    <option value="+254">+254</option>
                </datalist>
                <input type="tel" id="phone" name="telephone" placeholder="781674354" pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}" required><br><br>
                <label for="pwd">Password</label><br>
                <input type="password" id="pwd" name="password" placeholder="Password">         
        </form>
    </div>
    <div>
        <h3 class="calling">Select your gender:</h3>
        <form>
            <input type="radio" id="male" name="your favorite gender" value="Male">            
            <label for="male">Male</label><br>
            <input type="radio" id="female" name="your favorite gender" value="Female">
            <label for="female">Female</label>            
       </form>
    </div>
    <div>
            <h3 class="calling">
                Select your favorite car:
            </h3>
            <div>
                <form>
                    <label for="year">Select a year:</label>
                    <select id="year" name="select a year">
                        <option value="2020">2020</option>
                        <option value="2021">2021</option>
                        <option value="2022">2022</option>
                        <option value="2023">2023</option>
                    </select>
                </form>
            </div><br>
            <div>
                <form>
                    <input type="checkbox" id="car1" name="lambo" value="Lamborghini">
                    <label for="car1">Lamborghini</label><br>
                    <input type="checkbox" id="car2" name="rolls" value="Rolls Royce">
                    <label for="car2">Rolls Royce</label><br>
                    <input type="checkbox" id="car3" name="escalade" value="Cadilac Escalade">
                    <label for="car3">Cadilac Escalade</label><br><br>
                    <label for="qty">Quantity</label><br>
                    <input type="number" id="qty" name="quantity" min="1" max="5"><br><br>
                    <label for="bio">Your bio:</label><br>
                    <textarea name="bio" id="bio" cols="30" rows="5" placeholder="About you"></textarea><br><br>
                    <input type="submit" value="submit">
                    <a href="https://github.com/Selmy44" target="_blank"><input type="button" onclick="alert(Welcome to logins)" value="Click Me!"></a>

                    
                </form>
            </div>
    </div>
    
</body>
</html>
