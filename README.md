<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Ivy and Thyme - A luxury dining experience with exquisite cuisine and exceptional service.">
    <title>Ivy and Thyme - Luxury Dining</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=EB+Garamond&family=Nunito&family=Oswald&display=swap');

        body {
            font-family: 'Nunito', sans-serif;
            background-color: #efe9e1ff;
            color: #322d29ff;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #132620ff;
            color: #efe9e1ff;
            text-align: center;
            padding: 20px;
        }

        header h1 {
            font-family: 'Oswald', sans-serif;
            font-size: 3em;
            margin: 0;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
            text-align: center;
            background-color: #5e503fff;
        }

        nav ul li {
            display: inline-block;
            margin-right: 20px;
        }

        nav ul li a {
            text-decoration: none;
            font-family: 'Oswald', sans-serif;
            color: #efe9e1ff;
            font-size: 1.2em;
        }

        nav ul li a:hover {
            color: #d7ad61ff;
        }

        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
        }

        main h2 {
            font-family: 'EB Garamond', serif;
            color: #72383dff;
            font-size: 2.5em;
        }

        main p {
            font-size: 1.2em;
            line-height: 1.6;
        }

        main ul {
            list-style-type: none;
            padding: 0;
        }

        main ul li {
            font-family: 'EB Garamond', serif;
            font-size: 1.2em;
            color: #322d29ff;
            margin-bottom: 10px;
        }

        footer {
            background-color: #132620ff;
            color: #efe9e1ff;
            text-align: center;
            padding: 20px;
        }

        footer p {
            margin: 0;
            font-family: 'Oswald', sans-serif;
        }

        .image-container {
            display: flex; /* Align images side by side */
            justify-content: center; /* Center images */
            gap: 20px; /* Space between images */
            margin: 20px 0; /* Margin around the image container */
        }

        .image-container img {
            width: 45%; /* Set width of images to 45% for responsiveness */
            height: auto; /* Maintain aspect ratio */
        }

        .reservation-form, .contact-form {
            background-color: #c5ac8fff;
            padding: 20px;
            border-radius: 10px;
            color: #322d29ff;
            margin-top: 20px;
        }

        .reservation-form input, .reservation-form select, .reservation-form textarea,
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #322d29ff;
            border-radius: 5px;
            font-family: 'Nunito', sans-serif;
        }

        .reservation-form button, .contact-form button {
            background-color: #132620ff;
            color: #efe9e1ff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            font-family: 'Oswald', sans-serif;
            cursor: pointer;
        }

        .reservation-form button:hover, .contact-form button:hover {
            background-color: #72383dff;
        }
    </style>
</head>
<body>
    <header>
        <h1>Ivy and Thyme</h1>
    </header>

    <div class="container">
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#menu">Menu</a></li>
                <li><a href="#reservations">Reservations</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>

        <main>
            <!-- Home Section -->
            <section id="home">
                <h2>Welcome</h2>
                <p>Welcome to Ivy and Thyme, a luxury dining destination where elegance meets exceptional cuisine. Our restaurant offers a refined atmosphere, world-class service, and a menu crafted with the finest ingredients. Whether for a special occasion or an unforgettable evening, Ivy and Thyme promises a dining experience unlike any other.</p>                
                <div class="image-container">
                    <img src="https://visitbeloit.com/wp-content/uploads/MH_SM_40BW.jpg" alt="Restaurant Interior 2">
                    <img src="https://media.architecturaldigest.com/photos/55f9e3e34254f7de34561d50/16:9/w_1280,c_limit/dam-images-daily-2015-02-adrift-adrift-restaurant-01.jpg" alt="Restaurant Interior 3">
                </div>
            </section>

            <!-- About Us Section -->
            <section id="about">
                <h2>About Us</h2>
                <p>At Ivy and Thyme, we invite you to indulge in an unparalleled dining experience where luxury and taste come together. Our restaurant is a haven for those who appreciate the finer things in life, offering an exquisite ambiance, impeccable service, and a menu curated to perfection.</p>
                <p>Every dish at Ivy and Thyme is a masterpiece, crafted with the finest ingredients and inspired by global culinary traditions. Whether it’s a romantic dinner or a gathering of friends, we strive to make every moment extraordinary. Step into Ivy and Thyme and let us take you on a journey of gourmet excellence, where elegance and flavor are always in harmony.</p>
            </section>

            <!-- Menu Section -->
            <section id="menu">
                <h2>Menu</h2>

                <h3>Appetizers</h3>
                <ul>
                    <li>Truffle Arancini</li>
                    <li>Burrata Salad</li>
                    <li>Lobster Bisque</li>
                    <li>Tuna Tartare</li>
                </ul>

                <h3>Mains</h3>
                <ul>
                    <li>Filet Mignon with garlic mash</li>
                    <li>Chilean Sea Bass with saffron risotto</li>
                    <li>Wild Mushroom Risotto</li>
                    <li>Herb-Crusted Lamb Chops</li>
                </ul>

                <h3>Drinks</h3>
                <ul>
                    <li><strong>Cocktails:</strong> Ivy Martini, Thyme Lemonade</li>
                    <li><strong>Wine:</strong> Red & White Selection</li>
                    <li><strong>Non-Alcoholic:</strong> Fresh juices, Sparkling water</li>
                </ul>

                <h3>Desserts</h3>
                <ul>
                    <li>Chocolate Lava Cake</li>
                    <li>Crème Brûlée</li>
                    <li>Tiramisu</li>
                    <li>Seasonal Fruit Tart</li>
                </ul>
            </section>

            <!-- Reservations Section -->
            <section id="reservations">
                <h2>Reservations</h2>
                <div class="reservation-form">
                    <form action="#">
                        <label for="name">Name:</label>
                        <input type="text" id="name" name="name" required>

                        <label for="email">Email:</label>
                        <input type="email" id="email" name="email" required>

                        <label for="phone">Phone Number:</label>
                        <input type="tel" id="phone" name="phone" required>

                        <label for="date">Reservation Date:</label>
                        <input type="date" id="date" name="date" required>

                        <label for="time">Time:</label>
                        <select id="time" name="time" required>
                            <option value="6:00 PM">6:00 PM</option>
                            <option value="7:00 PM">7:00 PM</option>
                            <option value="8:00 PM">8:00 PM</option>
                        </select>

                        <label for="guests">Number of Guests:</label>
                        <input type="number" id="guests" name="guests" min="1" max="10" required>

                        <label for="requests">Special Requests:</label>
                        <textarea id="requests" name="requests" rows="4" placeholder="Let us know of any special requests..."></textarea>

                        <button type="submit">Reserve Now</button>
                    </form>
                </div>
            </section>

            <!-- Contact Section -->
            <section id="contact">
                <h2>Contact Us</h2>
                <div class="contact-form">
                    <form action="#">
                        <label for="contact-name">Name:</label>
                        <input type="text" id="contact-name" name="contact-name" required>

                        <label for="contact-email">Email:</label>
                        <input type="email" id="contact-email" name="contact-email" required>

                        <label for="contact-message">Message:</label>
                        <textarea id="contact-message" name="contact-message" rows="4" required></textarea>

                        <button type="submit">Send Message</button>
                    </form>
                </div>
            </section>
        </main>
    </div>

    <footer>
        <p>&copy; 2024 Ivy and Thyme. All rights reserved.</p>
    </footer>
</body>
</html>
