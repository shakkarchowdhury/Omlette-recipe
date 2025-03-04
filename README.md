# Omlette-recipe
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Omelette Recipe</title>
    <style>
        body {
            font-family: 'Poppins';
            background-color: #F6E9DE;
            margin: 0;
            padding: 20px;
            color: #5A3E36;
        }

        h1, #omelette {
            color: rgb(0, 0, 0);
            text-align: justify;
            font-weight: bold;
            font-family: "Merriweather";
            font-size: 30px;
        }

        .preparation-time {
            background-color: rgba(222, 195, 218, 0.507);
            text-align: justify;
            font-weight: bold;
            font-family: Arial;
            font-size: 20px;
            padding: 10px;
            border-radius: 5px;
        }

        .preparation-time ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
            text-align: justify;
        }

        .ingredients {
            background-color: rgba(209, 135, 100, 0.669);
            text-align: justify;
            font-weight: bold;
            font-family: Arial, sans-serif;
            font-size: 20px;
            padding: 10px;
            border-radius: 5px;
        }

        img {
            display: block;
            margin: auto;
            width: 600px;
            height: 300px;
            border-radius: 10px;
            padding: 10px;
        }

        #ins {
            color: rgb(0, 0, 0);
            text-align: justify;
            font-weight: bold;
            font-family: Arial, sans-serif;
            font-size: 20px;
        }
    </style>
</head>
<body>
    <img src="omlete.jpg" alt="Omelete">

    <h1 id="omelette">Simple Omelette Recipe</h1>

    <p>An easy and quick dish, perfect for any meal. This classic omelette combines beaten eggs cooked to perfection, optionally filled with your choice of cheese, vegetables, or meats.</p>

    <div class="preparation-time">
        <h3>Preparation Time</h3>
        <ul>
            <li><span>Total:</span> Approximately 10 minutes</li>
            <li>Preparation: 5 minutes</li>
            <li>Cooking: 5 minutes</li>
        </ul>
    </div>

    <div class="ingredients">
        <h3>Ingredients</h3>
        <ul>
            <li>2 large eggs</li>
            <li>1/4 cup milk</li>
            <li>1/4 teaspoon salt</li>
            <li>1/8 teaspoon pepper</li>
            <li>1 tablespoon butter</li>
        </ul>
    </div>

    <div class="instructions">
        <h3 id="ins">Instructions</h3>
        <ol>
            <li>Whisk together the eggs, milk, salt, and pepper in a bowl.</li>
            <li>Heat a skillet over medium heat. Add the butter and cook, stirring until melted, about 1 minute.</li>
            <li>Add the egg mixture to the skillet and cook, stirring constantly, until the eggs are cooked to your desired doneness, about 5 minutes.</li>
        </ol>
    </div>

    <div class="nutrition">
        <h3>Nutrition</h3>
        <p>The table below shows nutritional values per serving without the additional fillings.</p>
        <table border="1">
            <tr>
                <td>Calories</td>
                <td>277 kcal</td>
            </tr>
            <tr>
                <td>Carbs</td>
                <td>0 g</td>
            </tr>
            <tr>
                <td>Protein</td>
                <td>20 g</td>
            </tr>
            <tr>
                <td>Fat</td>
                <td>22 g</td>
            </tr>
        </table>
    </div>
</body>
</html>
