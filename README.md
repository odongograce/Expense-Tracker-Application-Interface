# Expense-Tracker-Application-Interface
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Expense Tracker Application interface</title>
    <style>
        body {
            font-family: Arial, Helvetica, sans-serif ; 
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
        }
        header {
            background-color: maroon;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        .main {
            max-width: 800px;
            margin: auto;
            background: white;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        table, th, td {
            border: 1px solid gainsboro;
        }
        th, td {
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
        form {
            margin-top: 20px;
        }
        form input[type="text"], form input[type="email"], form input[type="password"] {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            display: inline-block;
            border: 1px solid gainsboro;
            box-sizing: border-box;
        }
        form button {
            background-color: maroon;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
        }
        form button:hover {
            background-color: #a04551;
        }
        a{
            margin-top: 20px;
            display: flex;
           text-decoration: none;
        }
      
    </style>
</head>
<body>
  <header>
    <h1>Expense Tracker Application</h1>
  </header>  
  <div class="main">
    <h2>Welcome to the Expense Tracker Application</h2>
    <p>This tool will help you track your expenses and manage your budget efficiently.</p>

    <h3>Registration Form</h3>
    <form>
        <label for="name">Name:</label><br>
        <input type="text" id="name" name="name" placeholder="Enter your name" required><br>

        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" placeholder="Enter your email" required><br>

        <label for="password">Password:</label><br>
        <input type="password" id="password" name="password" placeholder="Enter yout password"><br>

        <button type="submit">Register</button>
    </form>

    <h3>User Information</h3>
    <table>
        <thead>
            <tr>
                <th>Name</th>
                <th>Email</th>
                <th>Phone Number</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Grace Odongo</td>
                <td>graceodongo@gmail.com</td>
                <td>254739458464</td>
            </tr>
            <tr>
                <td>Bonanza Lynn</td>
                <td>bonanzalynn23@gmail.com</td>
                <td>254732578575</td>
            </tr>
        </tbody>
    </table>

    <h3>Our Progress</h3>
    <img src="img\progress.jpg" alt="Image of progess graph" style="width: 400px; height:300px;"><br>

    <a href="https://google.com" target="_blank">Visit Google</a>
</div>
</body>
</html>
