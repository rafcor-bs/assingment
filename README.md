<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Caribbean Barbers</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;700&family=Lobster&display=swap"
        rel="stylesheet">
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
    <!-- Add Font Awesome CDN for the cart icon -->
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
        }

        header.sticky {
            position: fixed;
            top: 0;
            width: 100%;
            z-index: 1000;
            background: rgba(0, 0, 0, 0.9);
            transition: all 0.3s;
            padding: 10px 0;
        }

        .navbar-brand {
            font-size: 2rem;
            /* Increase brand name size */
        }

        .navbar-nav .nav-link {
            font-size: 1.1rem;
            /* Increase font size of nav links */
            padding: 10px 15px;
            /* Adjust padding for balance */
        }

        .navbar-toggler {
            font-size: 1.5rem;
            /* Increase the hamburger icon size */
        }

        .hero {
            position: relative;
            background: url('images.jpg') no-repeat center center/cover;
            color: white;
            text-align: center;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .hero-overlay {
            background: rgba(0, 0, 0, 0.5);
            width: 100%;
            height: 100%;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;
            padding: 20px;
        }

        .hero h1 {
            font-size: 3.5rem;
            font-family: 'Lobster', cursive;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 1.5rem;
            margin-bottom: 30px;
        }

        .hero .btn {
            font-size: 1.25rem;
            padding: 10px 20px;
            border-radius: 5px;
        }
    </style>
</head>

<body id="home" data-bs-spy="scroll" data-bs-target=".navbar" data-bs-offset="70" tabindex="0">

    <header>
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark sticky-top">
            <div class="container">
                <a class="navbar-brand" href="#">Caribbean Barbers</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                    aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav ml-auto">
                        <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
                        <li class="nav-item"><a class="nav-link" href="#services">Services</a></li>
                        <li class="nav-item"><a class="nav-link" href="#pricing">Pricing</a></li>
                        <li class="nav-item"><a class="nav-link" href="#gallery">Gallery</a></li>
                        <li class="nav-item"><a class="nav-link" href="#appointment">Appointment</a></li>
                        <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                    </ul>
                </div>

                <!-- Separate buttons container -->
                <div class="d-flex">
                    <button class="btn btn-primary ms-3">Book Now</button>
                    <!-- Add shopping cart icon -->
                    <a href="#cart-summary" class="btn btn-outline-light ms-3">
                        <i class="fas fa-shopping-cart ml-auto"></i> Cart
                    </a>
                </div>
            </div>
        </nav>
    </header>
    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-overlay">
            <div class="container">
                <h1>The Barber That Comes to You!</h1>
                <p>Your style, our expertise.</p>
                <a href="#appointment" class="btn btn-primary btn-lg">Book an Appointment</a>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="services py-5">
        <div class="container">
            <h2 class="text-center mb-5">Our Services</h2>
            <div class="row">
                <!-- Example Service Cards (Add more as needed) -->
                <div class="col-md-4">
                    <div class="card">
                        <img src="./download.png" class="card-img-top picture1" alt="Haircut">
                        <div class="card-body">
                            <h5 class="card-title">Haircuts</h5>
                            <p class="card-text">Enjoy the best personal grooming in the comfort of your own home with
                                our professional barbering services. Every precision cut is expertly tailored to enhance
                                your unique style and boost your confidence. Elevate your look with customized expert
                                cuts designed just for you!</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="./download (1).png" class="card-img-top picture1" alt="Shave">
                        <div class="card-body">
                            <h5 class="card-title">Shaves</h5>
                            <p class="card-text">Experience clean shaves with precision and expert techniques from our
                                professional barbers. Enjoy a smooth, comfortable finish that leaves your skin looking
                                and feeling its best.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="./images.png" class="card-img-top picture1" alt="Beard Trim">
                        <div class="card-body">
                            <h5 class="card-title">Beard Trims</h5>
                            <p class="card-text">Achieve the perfect beard shape with our skilled barbers. Enjoy expert
                                techniques and precision that enhance your facial hair, ensuring you look sharp and
                                polished every time.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="pricing" class="pricing py-5">
        <div class="container">
            <h2 class="text-center mb-5">Our Pricing</h2>
            <div class="row">
                <!-- Wet Shaving -->
                <div class="col-md-4">
                    <div class="card">
                        <img src="./b27874b9bf3605a965373ea6177ac9f1.jpg" class="card-img-top" alt="Wet Shaving">
                        <div class="card-body">
                            <h5 class="card-title">Wet Shaving</h5>
                            <p class="card-text">&pound;19.99</p>
                            <button class="btn btn-primary" onclick="addToCart('Wet Shaving', 20)">Add to Cart</button>
                        </div>
                    </div>
                </div>
                <!-- Beard Trim -->
                <div class="col-md-4">
                    <div class="card">
                        <img src="./8f229751dd2b17e026dc838fb50d73ec.jpg" class="card-img-top" alt="Beard Trim">
                        <div class="card-body">
                            <h5 class="card-title">Beard Trim</h5>
                            <p class="card-text">&pound;29.99</p>
                            <button class="btn btn-primary" onclick="addToCart('Beard Trim', 25)">Add to Cart</button>
                        </div>
                    </div>
                </div>
                <!-- Haircut -->
                <div class="col-md-4">
                    <div class="card">
                        <img src="./567456187d1e9ab85b2157bd6f2c8cd8.jpg" class="card-img-top" alt="Haircut">
                        <div class="card-body">
                            <h5 class="card-title">Haircut</h5>
                            <p class="card-text">&pound;49.99</p>
                            <button class="btn btn-primary" onclick="addToCart('Haircut', 45)">Add to Cart</button>
                        </div>
                    </div>
                </div>
            </div>
            <!-- Gallery Section -->
            <section id="gallery" class="gallery py-5">
                <div class="container">
                    <h2 class="text-center mb-5">Our Gallery</h2>
                    <div class="row g-4"> <!-- Add spacing between grid items -->
                        <div class="col-6 col-md-3">
                            <div class="gallery-item">
                                <img src="./73dad7d408cf03fb3d5fbbf2734c4227 (1).jpg" class="img-fluid" alt="Gallery">
                            </div>
                        </div>
                        <div class="col-6 col-md-3">
                            <div class="gallery-item">
                                <img src="./6fc83d1d89ce7f0e6c3df83190f6302a.jpg" class="img-fluid" alt="Gallery">
                            </div>
                        </div>
                        <div class="col-6 col-md-3">
                            <div class="gallery-item">
                                <img src="./c90b3f3505929a973ea66e97caadfca4.jpg" class="img-fluid" alt="Gallery">
                            </div>
                        </div>
                        <div class="col-6 col-md-3">
                            <div class="gallery-item">
                                <img src="./b2c45d43141cd655f22b2df9b9d737dc.jpg" class="img-fluid" alt="Gallery">
                            </div>
                        </div>
                    </div>
                </div>
            </section>

            <!-- Appointment Section -->
            <section id="appointment" class="appointment py-5">
                <div class="container">
                    <h2 class="text-center mb-5">Book an Appointment</h2>
                    <form>
                        <div class="mb-3">
                            <label for="name" class="form-label">Name</label>
                            <input type="text" class="form-control" id="name" required>
                        </div>
                        <div class="mb-3">
                            <label for="email" class="form-label">Email</label>
                            <input type="email" class="form-control" id="email" required>
                        </div>
                        <div class="mb-3">
                            <label for="phone" class="form-label">Phone Number</label>
                            <input type="tel" class="form-control" id="phone" required>
                        </div>
                        <div class="mb-3">
                            <label for="appointment-date" class="form-label">Preferred Date</label>
                            <input type="date" class="form-control" id="appointment-date" required>
                        </div>
                        <div class="mb-3">
                            <label for="service" class="form-label">Service</label>
                            <select class="form-control" id="service" required>
                                <option value="Haircut">Haircut</option>
                                <option value="Beard Trim">Beard Trim</option>
                                <option value="Shave">Shave</option>
                            </select>
                        </div>
                        <button type="submit" class="btn btn-primary">Book Appointment</button>
                    </form>
                </div>
            </section>

            <!-- Cart Summary Section at the Bottom -->
            <div class="cart-summary-container">
                <div id="cart-summary">
                    <h3>Your Cart</h3>
                    <ul id="cart-items" class="list-group">
                        <!-- Cart items will be displayed here -->
                    </ul>
                    <div id="cart-total"></div> <!-- Total will be displayed here -->
                    <button class="btn btn-success mt-3" onclick="checkout()">Proceed to Checkout</button>
                </div>
            </div>
    </section>
    <div id="cart-total"></div>
    </div>

    <script>
        window.addEventListener("scroll", function () {
            var header = document.querySelector("header");
            header.classList.toggle("sticky", window.scrollY > 0);
        });
    </script>
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Proceed to Checkout - Caribbean Barbers</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;700&family=Lobster&display=swap"
        rel="stylesheet">
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
    <!-- Add Font Awesome CDN for the cart icon -->
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
        }

        .container {
            margin-top: 50px;
        }

        .cart-summary {
            margin-bottom: 30px;
        }

        .checkout-form .form-control {
            margin-bottom: 15px;
        }
    </style>
</head>

<body>

    <div class="container">
        <h1 class="text-center mb-5">Proceed to Checkout</h1>

        <!-- Cart Summary -->
        <div class="cart-summary">
            <h3>Your Cart</h3>
            <ul id="cart-items" class="list-group">
                <!-- Cart items will be displayed here -->
            </ul>
            <div id="cart-total" class="mt-3">
                <!-- Total will be displayed here -->
            </div>
        </div>

        <!-- Checkout Form -->
        <div class="checkout-form">
            <h3>Billing Information</h3>
            <form id="checkout-form">
                <div class="mb-3">
                    <label for="full-name" class="form-label">Full Name</label>
                    <input type="text" class="form-control" id="full-name" required>
                </div>
                <div class="mb-3">
                    <label for="email" class="form-label">Email</label>
                    <input type="email" class="form-control" id="email" required>
                </div>
                <div class="mb-3">
                    <label for="address" class="form-label">Shipping Address</label>
                    <input type="text" class="form-control" id="address" required>
                </div>
                <div class="mb-3">
                    <label for="phone" class="form-label">Phone Number</label>
                    <input type="tel" class="form-control" id="phone" required>
                </div>
                <button type="submit" class="btn btn-success">Complete Purchase</button>
            </form>
        </div>
    </div>

    <!-- Script for Cart Management and Checkout -->
    <script>
        // Initialize an empty cart
        let cart = [];

        // Function to add items to the cart
        function addToCart(service, price) {
            cart.push({ service, price });
            displayCart();
        }

        // Display cart items
        function displayCart() {
            const cartItems = document.getElementById('cart-items');
            cartItems.innerHTML = ''; // Clear previous cart items

            let total = 0;
            cart.forEach(item => {
                const listItem = document.createElement('li');
                listItem.classList.add('list-group-item');
                listItem.textContent = `${item.service} - £${item.price}`;
                cartItems.appendChild(listItem);
                total += item.price;
            });

            // Display the total amount
            const cartTotal = document.getElementById('cart-total');
            cartTotal.textContent = `Total: £${total}`;
        }

        // Handle checkout form submission
        document.getElementById('checkout-form').addEventListener('submit', function (e) {
            e.preventDefault();
            const name = document.getElementById('full-name').value;
            const email = document.getElementById('email').value;
            const address = document.getElementById('address').value;
            const phone = document.getElementById('phone').value;

            if (cart.length > 0) {
                alert(`Thank you for your purchase, ${name}! We will send a confirmation to ${email}.`);
                // Reset cart after successful checkout
                cart = [];
                displayCart();
                document.getElementById('checkout-form').reset();
            } else {
                alert("Your cart is empty.");
            }
        });

        // For demonstration, pre-add some items to the cart
        addToCart('Haircut', 45);
        addToCart('Beard Trim', 25);
    </script>

    <!-- Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>

</html>
