# khatu shyam online shopping
Khatu Shyam Online Shopping: Your Trusted Online Destination for All Things Divine and Traditional  Welcome to Khatu Shyam Online Shopping, your one-stop shop for all spiritual and traditional needs. 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Shopping Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background-color: #333;
            overflow: hidden;
        }

        nav a {
            color: white;
            padding: 14px 20px;
            text-align: center;
            text-decoration: none;
            float: left;
        }

        nav a:hover {
            background-color: #ddd;
            color: black;
        }

        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            padding: 20px;
        }

        .product {
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            width: 250px;
            margin: 20px;
            padding: 20px;
            text-align: center;
        }

        .product img {
            width: 100%;
            height: auto;
            border-radius: 8px;
        }

        .product h3 {
            font-size: 18px;
            margin: 15px 0;
        }

        .product p {
            color: #555;
        }

        .product .price {
            font-size: 20px;
            font-weight: bold;
            color: #4CAF50;
        }

        .product button {
            background-color: #4CAF50;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .product button:hover {
            background-color: #45a049;
        }

        #cart {
            position: fixed;
            top: 20px;
            right: 20px;
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border-radius: 50%;
            cursor: pointer;
        }

        #cart:active {
            background-color: #45a049;
        }

        .cart-popup {
            display: none;
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            width: 300px;
        }

        .cart-popup h3 {
            margin: 0 0 15px;
            text-align: center;
        }

        .cart-popup ul {
            list-style-type: none;
            padding: 0;
        }

        .cart-popup ul li {
            margin-bottom: 10px;
        }
