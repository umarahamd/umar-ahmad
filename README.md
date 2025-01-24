<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" 
          content="width=device-width, 
                   initial-scale=1.0">
    <link rel="stylesheet" 
          href="styles.css">
    <title>Grocery Store</title>
</head>

<body>

    <header>
        <div class="navbar">
            <div class="logo">
                <span>
                    <p>Grocery Store</p>
                </span>
            </div>
            <nav>
                <ul>
                    <li>
                        <a href="#home">
                            Home
                        </a>
                    </li>
                    <li>
                        <a href="#vegetables">
                            Vegetables
                        </a>
                    </li>
                    <li>
                        <a href="#fruits">
                            Fruits
                        </a>
                    </li>
                </ul>
            </nav>
            <div class="search">
                <input type="text" 
                       placeholder="Search products...">
                <button>Search</button>
            </div>
        </div>
    </header>

    <div class="container">
        <section>
            <h2 id="vegetables">
                Vegetables
            </h2>

            <div class="category">
                <div class="product">
                    <div class="image-placeholder 
                                image-placeholder1">
                        <img src=
"https://media.geeksforgeeks.org/wp-content/uploads/20240104152640/carrot-icon.png"
                             alt="grocery">
                    </div>
                    <h3>Carrot</h3>
                    <p class="price">$1.99/1kg</p>
                    <div class="qyt">
                        <label for="quantity_vegetable1">
                            Quantity:
                        </label>
                        <input type="number" 
                               id="quantity_vegetable1" 
                               value="1">
                    </div>
                    <div class="productbtns">
                        <button>
                            Add to Cart
                        </button>
                        <button>
                            Buy Now
                        </button>
                    </div>
                </div>

                <div class="product">
                    <div class="image-placeholder 
                                image-placeholder2">
                        <img src=
"https://media.geeksforgeeks.org/wp-content/uploads/20240104153932/tomato-icon.png"
                            alt="grocery">
                    </div>
                    <h3>Tomato</h3>
                    <p class="price">$1.49/1kg</p>
                    <div class="qyt">
                        <label for="quantity_vegetable2">
                            Quantity:
                        </label>
                        <input type="number" 
                               id="quantity_vegetable2" 
                               value="1">
                    </div>
                    <div class="productbtns">
                        <button>Add to Cart</button>
                        <button>Buy Now</button>
                    </div>
                </div>

                <div class="product">
                    <div class="image-placeholder 
                                image-placeholder3">
                        <img src=
"https://media.geeksforgeeks.org/wp-content/uploads/20240104153754/pumpkin-icon.png"
                            alt="grocery">
                    </div>
                    <h3>Pumpkin</h3>
                    <p class="price">$2.99/1kg</p>
                    <div class="qyt">
                        <label for="quantity_vegetable3">
                            Quantity:
                        </label>
                        <input type="number" 
                               id="quantity_vegetable3" 
                               value="1">
                    </div>
                    <div class="productbtns">
                        <button>Add to Cart</button>
                        <button>Buy Now</button>
                    </div>
                </div>

                <div class="product">
                    <div class="image-placeholder 
                                image-placeholder4">
                        <img src=
"https://media.geeksforgeeks.org/wp-content/uploads/20240104153652/eggplant-icon.png"
                            alt="grocery">
                    </div>
                    <h3>Brinjal</h3>
                    <p class="price">$1.79/1kg</p>
                    <div class="qyt">
                        <label for="quantity_vegetable4">
                            Quantity:
                        </label>
                        <input type="number" 
                               id="quantity_vegetable4" 
                               value="1">
                    </div>
                    <div class="productbtns">
                        <button>Add to Cart</button>
                        <button>Buy Now</button>
                    </div>
                </div>
            </div>
        </section>

        <section>
            <h2 id="fruits">Fruits</h2>
            <div class="category">
                <div class="product">
                    <div class="image-placeholder image-placeholder5">
                        <img src=
"https://media.geeksforgeeks.org/wp-content/uploads/20240104153254/fresh-apple-icon.png"
                            alt="grocery">
                    </div>
                    <h3>Apple</h3>
                    <p class="price">$2.49/1kg</p>
                    <div class="qyt">
                        <label for="quantity_fruit1">
                            Quantity:
                        </label>
                        <input type="number" 
                               id="quantity_fruit1"
                               value="1">
                    </div>
                    <div class="productbtns">
                        <button>Add to Cart</button>
                        <button>Buy Now</button>
                    </div>
                </div>

                <div class="product">
                    <div class="image-placeholder 
                                image-placeholder6">
                        <img src=
"https://media.geeksforgeeks.org/wp-content/uploads/20240104153407/bananas-icon.png"
                            alt="grocery">
                    </div>
                    <h3>Banana</h3>
                    <p class="price">$0.99/1kg</p>
                    <div class="qyt">
                        <label for="quantity_fruit2">
                            Quantity:
                        </label>
                        <input type="number" 
                               id="quantity_fruit2" 
                               value="1">
                    </div>
                    <div class="productbtns">
                        <button>Add to Cart</button>
                        <button>Buy Now</button>
                    </div>
                </div>

                <div class="product">
                    <div class="image-placeholder 
                                image-placeholder7">
                        <img src=
"https://media.geeksforgeeks.org/wp-content/uploads/20240104153523/orange-icon.png"
                            alt="grocery">
                    </div>
                    <h3>Orange</h3>
                    <p class="price">$0.79/1kg</p>
                    <div class="qyt">
                        <label for="quantity_fruit4">
                            Quantity:
                        </label>
                        <input type="number" 
                               id="quantity_fruit4" 
                               value="1">
                    </div>
                    <div class="productbtns">
                        <button>Add to Cart</button>
                        <button>Buy Now</button>
                    </div>
                </div>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2023 Grocery Store.
            All rights reserved.
        </p>
    </footer>

</body>

</html>
