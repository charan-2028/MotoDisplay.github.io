<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bikes Showcase</title>
    <style>
        /* Global Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #000; /* Black background */
            color: #eee; /* Light gray text for readability */
        }

        /* Header */
        header {
            background: linear-gradient(135deg, #1a1a1a, #333);
            color: #fff;
            padding: 1.5rem 0;
            text-align: center;
            font-size: 2rem;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.5);
        }

        /* Navigation */
        nav {
            background: linear-gradient(135deg, #222, #444);
            display: flex;
            justify-content: center;
            border-bottom: 1px solid #555;
        }

        nav a {
            color: #ddd;
            text-decoration: none;
            padding: 1rem 1.5rem;
            display: block;
            font-size: 1.1rem;
            transition: all 0.3s ease;
        }

        nav a:hover {
            background-color: #555;
            color: #fff;
            border-radius: 5px;
        }

        /* Section Styles */
        section {
            padding: 2rem;
        }

        section h2 {
            font-size: 1.8rem;
            color: #fff;
            margin-bottom: 1rem;
            border-bottom: 2px solid #444;
            display: inline-block;
            padding-bottom: 0.5rem;
        }

        section p {
            font-size: 1.1rem;
            line-height: 1.6;
            color: #ccc;
        }

        /* Gallery Grid */
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1.5rem;
        }

        .gallery img {
            width: 100%;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(255, 255, 255, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .gallery img:hover {
            transform: scale(1.05);
            box-shadow: 0 6px 12px rgba(255, 255, 255, 0.2);
        }

        .bike-info {
            margin-top: 0.5rem;
            font-size: 1rem;
            color: #bbb;
            line-height: 1.5;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 1.5rem;
            background: linear-gradient(135deg, #1a1a1a, #333);
            color: #ddd;
            font-size: 1rem;
            box-shadow: 0 -4px 6px rgba(0, 0, 0, 0.5);
        }

        footer p {
            margin: 0;
        }

        /* Media Queries */
        @media (max-width: 600px) {
            nav {
                flex-wrap: wrap;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Explore the World of Bikes</h1>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#mountain">Mountain Bikes</a>
        <a href="#road">Road Bikes</a>
        <a href="#hybrid">Hybrid Bikes</a>
        <a href="#electric">Electric Bikes</a>
    </nav>

    <section id="home">
        <h2>Welcome</h2>
        <p>Discover the best bikes for every terrain and purpose. Navigate through our sections to learn more about different bike types and their unique features.</p>
    </section>

    <section id="mountain">
        <h2>Mountain Bikes</h2>
        <div class="gallery">
            <div>
                <img src="https://raw.githubusercontent.com/charan-2028/BikeHub.GITHUB.1OQ/d371e3dd7b11df2dfb62a6013797b68c6a723e98/v1.jpg" alt="Mountain Bike 1 View 1">
                <img src="https://raw.githubusercontent.com/charan-2028/BikeHub.GITHUB.1OQ/d371e3dd7b11df2dfb62a6013797b68c6a723e98/v2.jpg" alt="Mountain Bike 1 View 2">
                <img src="https://raw.githubusercontent.com/charan-2028/BikeHub.GITHUB.1OQ/d371e3dd7b11df2dfb62a6013797b68c6a723e98/v3.jpg" alt="Mountain Bike 1 View 3">
                <p class="bike-info">
                    The Triumph Tiger 900 is a versatile, middleweight adventure motorcycle designed for both on-road and off-road performance. It is part of Triumph’s iconic Tiger series and offers a perfect balance of power, technology, and comfort, making it a favorite among adventure bike enthusiasts.
                </p>
            </div>
        </div>
    </section>

    <section id="road">
        <h2>Road Bikes</h2>
        <div class="gallery">
            <div>
                <img src="https://raw.githubusercontent.com/charan-2028/BikeHub.GITHUB.1OQ/23874dd5fe62fa8b9e7a70ed208c9edee315bdaf/r1.jpg" alt="Road Bike 1 View 1">
                <img src="https://raw.githubusercontent.com/charan-2028/BikeHub.GITHUB.1OQ/23874dd5fe62fa8b9e7a70ed208c9edee315bdaf/r2.jpg" alt="Road Bike 1 View 2">
                <img src="https://raw.githubusercontent.com/charan-2028/BikeHub.GITHUB.1OQ/23874dd5fe62fa8b9e7a70ed208c9edee315bdaf/r3.jpg" alt="Road Bike 1 View 3">
                <p class="bike-info">
                    The Royal Enfield Super Meteor 650 is a highly anticipated cruiser motorcycle from Royal Enfield, leveraging their renowned 650cc parallel-twin platform. With a classic cruiser design and advanced features, it’s a favorite for long-distance riders.
                </p>
            </div>
        </div>
    </section>

    <section id="hybrid">
        <h2>Hybrid Bikes</h2>
        <div class="gallery">
            <div>
                <img src="https://raw.githubusercontent.com/charan-2028/BikeHub.GITHUB.1OQ/0a2e5559331eeccc58b480b1890d1deaaa60fb72/cq5dam.thumbnail.600.600%20(1).png" alt="Hybrid Bike 1 View 1">
                <img src="https://raw.githubusercontent.com/charan-2028/BikeHub.GITHUB.1OQ/0a2e5559331eeccc58b480b1890d1deaaa60fb72/cq5dam.thumbnail.600.600%20(2).png" alt="Hybrid Bike 1 View 2">
                <img src="https://raw.githubusercontent.com/charan-2028/BikeHub.GITHUB.1OQ/0a2e5559331eeccc58b480b1890d1deaaa60fb72/cq5dam.thumbnail.600.600%20(2).png" alt="Hybrid Bike 1 View 3">
                <p class="bike-info">
                    The Kawasaki Ninja 7 Hybrid combines a parallel-twin engine with an electric motor, offering performance and eco-friendliness in a futuristic design.
                </p>
            </div>
        </div>
    </section>

    <section id="electric">
        <h2>Electric Bikes</h2>
        <div class="gallery">
            <div>
                <img src="https://raw.githubusercontent.com/charan-2028/BikeHub.GITHUB.1OQ/68f3713e63ebe1dd8872f99ab4737f491ea8d56a/1.e.jpg" alt="Electric Bike 1 View 1">
                <img src="https://raw.githubusercontent.com/charan-2028/BikeHub.GITHUB.1OQ/68f3713e63ebe1dd8872f99ab4737f491ea8d56a/2.e.jpg" alt="Electric Bike 1 View 2">
                <img src="https://raw.githubusercontent.com/charan-2028/BikeHub.GITHUB.1OQ/68f3713e63ebe1dd8872f99ab4737f491ea8d56a/3.e.jpg" alt="Electric Bike 1 View 3">
                <p class="bike-info">
                    The Zero SR/F is a premium electric motorcycle combining cutting-edge technology with sleek design, offering impressive performance and sustainability.
                </p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Bikes Showcase. All rights reserved.</p>
    </footer>

    <script>
        console.log('Welcome to Bikes Showcase!');
    </script>
</body>
</html>
