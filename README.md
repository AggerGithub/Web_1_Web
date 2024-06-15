<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Expense Tracker Application</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to the Expense Tracker Application</h1>
    </header>
    <main>
        <section>
            <h2>Track Your Expenses Effortlessly</h2>
            <p>Manage your finances by keeping track of your expenses and income. Register now to get started!</p>
        </section>
        <section>
            <h2>Registration Form</h2>
            <form action="/submit-registration" method="POST">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required><br><br>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required><br><br>
                <label for="phone">Phone Number:</label>
                <input type="tel" id="phone" name="phone" required><br><br>
                <button type="submit">Register</button>
            </form>
        </section>
        <section>
            <h2>User Information</h2>
            <table border="1">
                <tr>
                    <th>Name</th>
                    <th>Email</th>
                    <th>Phone Number</th>
                </tr>
                <tr>
                    <td>Agger Castory</td>
                    <td>aggercastorie@gmail.com</td>
                    <td>123-456-7890</td>
                </tr>
                <tr>
                    <td>Blandie Shammie</td>
                    <td>blandieshammie@gmail.com</td>
                    <td>098-765-4321</td>
                </tr>
            </table>
        </section>
        <section>
            <h2>App Image</h2>
            <img src="expense-tracker-image.jpg" alt="Expense Tracker">
        </section>
        <section>
            <h2>External Link</h2>
            <p>For more information, visit <a href="https://google.com" target="_blank">Google</a>.</p>
        </section>
    </main>
</body>
</html>
