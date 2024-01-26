<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Stall Review</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1em;
        }

        main {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: #333;
        }

        .review {
            margin-bottom: 20px;
            padding: 15px;
            background-color: #f9f9f9;
            border-radius: 5px;
        }

        footer {
            text-align: center;
            padding: 1em;
            background-color: #333;
            color: #fff;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Stall Reviews</h1>
</header>

<main>
    <h2>Latest Reviews</h2>

    <div class="review">
        <h3>Stall Name</h3>
        <p>Review: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ac leo at est tempus cursus.</p>
        <p>Rating: 4/5</p>
    </div>

    <!-- Add more reviews as needed -->

    <h2>Write a Review</h2>

    <form action="submit_review.php" method="post">
        <label for="stallName">Stall Name:</label>
        <input type="text" id="stallName" name="stallName" required>

        <label for="review">Your Review:</label>
        <textarea id="review" name="review" rows="4" required></textarea>

        <label for="rating">Rating (1-5):</label>
        <input type="number" id="rating" name="rating" min="1" max="5" required>

        <button type="submit">Submit Review</button>
    </form>
</main>

<footer>
    &copy; 2024 Stall Reviews
</footer>

</body>
</html>
