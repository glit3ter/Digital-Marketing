<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Digital Marketing Company</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
        }
        header {
            background: linear-gradient(to right, #4e54c8, #8f94fb);
            color: white;
            text-align: center;
            padding: 50px 20px;
            position: relative;
        }
        header h1 {
            font-size: 3rem;
            margin: 0;
            animation: fadeIn 2s ease-in-out;
        }
        header p {
            font-size: 1.2rem;
            margin: 20px 0;
            animation: fadeIn 2.5s ease-in-out;
        }
        header a {
            background-color: #ff5733;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1rem;
            animation: fadeIn 3s ease-in-out;
        }
        header a:hover {
            background-color: #c13b18;
        }
        @keyframes fadeIn {
            0% { opacity: 0; transform: translateY(-20px); }
            100% { opacity: 1; transform: translateY(0); }
        }
        .service {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 50px;
            background: #f7f7f7;
            border-bottom: 1px solid #ddd;
        }
        .service h2 {
            color: #333;
        }
        form {
            max-width: 500px;
            width: 100%;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        form label {
            display: block;
            margin: 10px 0 5px;
            color: #555;
        }
        form input, form textarea, form select {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        form input[type="submit"] {
            background-color: #4e54c8;
            color: white;
            border: none;
            cursor: pointer;
        }
        form input[type="submit"]:hover {
            background-color: #3c41a3;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #333;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to [Your Company Name]</h1>
        <p>Your trusted partner in digital marketing and design solutions.</p>
        <a href="#services">Explore Services</a>
    </header>

    <section id="services">
        <div class="service">
            <h2>Motion Graphic Design</h2>
            <p>We create stunning motion graphics that tell your story effectively.</p>
            <form>
                <label for="name">Full Name:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email Address:</label>
                <input type="email" id="email" name="email" required>

                <label for="description">Project Description:</label>
                <textarea id="description" name="description" rows="5" required></textarea>

                <label for="date">Preferred Delivery Date:</label>
                <input type="date" id="date" name="date" required>

                <label for="file">Upload Files:</label>
                <input type="file" id="file" name="file">

                <label for="phone">Contact Number:</label>
                <input type="tel" id="phone" name="phone" required>

                <input type="submit" value="Submit Request">
            </form>
        </div>

        <div class="service">
            <h2>Digital Marketing</h2>
            <p>Boost your online presence with our tailored digital marketing strategies.</p>
            <!-- Add form here with similar structure -->
        </div>

        <div class="service">
            <h2>Campaign Launch</h2>
            <p>Let us plan and execute marketing campaigns that deliver results.</p>
            <!-- Add form here with similar structure -->
        </div>

        <div class="service">
            <h2>Account Management</h2>
            <p>Professional management of your social media and marketing accounts.</p>
            <!-- Add form here with similar structure -->
        </div>
    </section>

    <footer>
        &copy; 2024 [Your Company Name]. All rights reserved.
    </footer>
</body>
</html>
