# login_page
a new login page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Glassmorphism</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <form>
        <h1> LOGIN</h1>
        <label>Username</label>
        <input type ="text">
        <label>Password</label>
        <input type ="text">
        <button>login</button>
        <a>Forgrt password?</a>
    </form>
</body>
</html>

@import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Poppins", sans-serif;
    cursor: pointer;
}

body {
    height: 100vh;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    background: linear-gradient(to right, #3f5efb, rgb(0, 255, 162));
}

form {
    width: 25rem;
    height: 28rem;
    display: flex;
    flex-direction: column;
    background: rgba(255, 255, 255, 0.06);
    box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
    border-radius: 30px;
    border-left: 1px solid rgba(255, 255, 255, 0.3);
    border-top: 1px solid rgba(255, 255, 255, 0.3);
    margin-top: 6%;
}


h1 {
    font-size: 50px;
    text-align: center;
    color: white;
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
    letter-spacing: 3px;
    margin-top: 0;
    opacity: 0.7;
}

label {
    font-size: 20px;
    color: white;
    margin-left: 10%;
    opacity: 0.8;
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
}

input {
    width: 80%;
    margin: 5% auto;
    margin-bottom: 8%;
    border: none;
    outline: none;
    background: transparent;
    color: white;
    border-bottom: 1px solid rgba(255, 255, 255, 0.6);
    opacity: 0.8;
}

button {
    width: 50%;
    margin: 3% auto;
    color: white;
    font-size: 15px;
    opacity: 0.8;
    background-color: rgba(255, 255, 255, 0.06);
    padding: 10px 30px;
    border: none;
    outline: none;
    border-radius: 20px;
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
    box-shadow: 3px 3px 5px rgba(31, 38, 135, 0.37); /* Fixed parentheses */
    border-left: 1px solid rgba(255, 255, 255, 0.3);
    border-top: 1px solid rgba(255, 255, 255, 0.3);
}

a {
    font-size: 12px;
    text-align: center;
    color: white;
    opacity: 0.8;
}
