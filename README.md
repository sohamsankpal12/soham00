# soham00
#mobile shop
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mobile Shop</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
        }
        header {
            background-color: #4CAF50;
            color: yellow;
            padding: 20px;
            text-align: center;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            padding: 20px;
        }
        .product {
            background-color: skyblue;
            border: 1px solid #ddd;
            border-radius: 5px;
            margin: 20px;
            padding: 20px;
            width: 300px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .product img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }
        .product h2 {
            font-size: 20px;
            color: #333;
        }
        .product p {
            font-size: 16px;
            color: #666;
        }
        .product .price {
            font-size: 18px;
            color: #e67e22;
            margin-top: 10px;
        }
        .product button {
            background-color: #4CAF50;
            color: black;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 10px;
        }
        .product button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to Mobile Shop</h1>
    </header>

    <div class="container">

        <div class="product">
            <img src="https://via.placeholder.com/300x400.png?text=Mobile+1" alt="Mobile 1">
            <h2>Mobile 1</h2>
            <p>Latest smartphone with amazing features.</p>
            <div class="price">Rs 10,000</div>
            <button>Buy Now</button>
        </div>

        <div class="product">
            <img src="https://via.placeholder.com/300x400.png?text=Mobile+2" alt="Mobile 2">
            <h2>Mobile 2</h2>
            <p>High-performance phone with sleek design.</p>
            <div class="price">Rs 18,000</div>
            <button>Buy Now</button>
        </div>

        <div class="product">
            <img src="https://via.placeholder.com/300x400.png?text=Mobile+3" alt="Mobile 3">
            <h2>Mobile 3</h2>
            <p>Affordable smartphone with all the essentials.</p>
            <div class="price">Rs 20,000</div>
            <button>Buy Now</button>
        </div>

        <div class="product">
            <img src="https://via.placeholder.com/300x400.png?text=Mobile+4" alt="Mobile 4">
            <h2>Mobile 4</h2>
            <p>Flagship phone with top-of-the-line specs.</p>
            <div class="price">Rs 30,000</div>
            <button>Buy Now</button>
        </div>

    </div>

</body>
</html>

