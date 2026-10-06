<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Food Menu</title>

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
</head>

<body class="bg-gray-100">

    <!-- Header -->
    <header class="bg-orange-500 text-white text-center py-6">
        <h1 class="text-3xl font-bold">Our Food Menu</h1>
        <p class="mt-2">Delicious food for everyone</p>
    </header>

    <!-- Food Menu Section -->
    <section class="max-w-6xl mx-auto px-6 py-10">

        <h2 class="text-2xl font-bold text-center mb-8">
            Popular Dishes
        </h2>

        <!-- Grid -->
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">

            <!-- Card 1 -->
            <div class="bg-white rounded-lg shadow-md overflow-hidden">
                <img 
                    src="https://images.unsplash.com/photo-1565299624946-b28f40a0ae38"
                    alt="Pizza"
                    class="w-full h-48 object-cover"
                >

                <div class="p-5">
                    <h3 class="text-xl font-bold text-gray-800">
                        Cheese Pizza
                    </h3>

                    <p class="text-gray-600 mt-2">
                        Delicious pizza topped with fresh cheese,
                        vegetables and tasty herbs.
                    </p>

                    <button class="mt-4 bg-orange-500 text-white px-5 py-2 rounded hover:bg-orange-600">
                        Order Now
                    </button>
                </div>
            </div>

            <!-- Card 2 -->
            <div class="bg-white rounded-lg shadow-md overflow-hidden">
                <img 
                    src="https://images.unsplash.com/photo-1568901346375-23c9450c58cd"
                    alt="Burger"
                    class="w-full h-48 object-cover"
                >

                <div class="p-5">
                    <h3 class="text-xl font-bold text-gray-800">
                        Cheese Burger
                    </h3>

                    <p class="text-gray-600 mt-2">
                        Juicy burger with fresh vegetables,
                        cheese and a special sauce.
                    </p>

                    <button class="mt-4 bg-orange-500 text-white px-5 py-2 rounded hover:bg-orange-600">
                        Order Now
                    </button>
                </div>
            </div>

            <!-- Card 3 -->
            <div class="bg-white rounded-lg shadow-md overflow-hidden">
                <img 
                    src="https://images.unsplash.com/photo-1550547660-d9450f859349"
                    alt="French Fries"
                    class="w-full h-48 object-cover"
                >

                <div class="p-5">
                    <h3 class="text-xl font-bold text-gray-800">
                        French Fries
                    </h3>

                    <p class="text-gray-600 mt-2">
                        Crispy golden french fries served
                        with delicious seasoning.
                    </p>

                    <button class="mt-4 bg-orange-500 text-white px-5 py-2 rounded hover:bg-orange-600">
                        Order Now
                    </button>
                </div>
            </div>

            <!-- Card 4 -->
            <div class="bg-white rounded-lg shadow-md overflow-hidden">
                <img 
                    src="https://images.unsplash.com/photo-1601050690597-df0568f70950"
                    alt="Samosa"
                    class="w-full h-48 object-cover"
                >

                <div class="p-5">
                    <h3 class="text-xl font-bold text-gray-800">
                        Samosa
                    </h3>

                    <p class="text-gray-600 mt-2">
                        Crispy samosa filled with spicy potatoes
                        and delicious Indian spices.
                    </p>

                    <button class="mt-4 bg-orange-500 text-white px-5 py-2 rounded hover:bg-orange-600">
                        Order Now
                    </button>
                </div>
            </div>

            <!-- Card 5 -->
            <div class="bg-white rounded-lg shadow-md overflow-hidden">
                <img 
                    src="https://images.unsplash.com/photo-1551024506-0bccd828d307"
                    alt="Donut"
                    class="w-full h-48 object-cover"
                >

                <div class="p-5">
                    <h3 class="text-xl font-bold text-gray-800">
                        Chocolate Donut
                    </h3>

                    <p class="text-gray-600 mt-2">
                        Soft and delicious donut covered with
                        rich chocolate and toppings.
                    </p>

                    <button class="mt-4 bg-orange-500 text-white px-5 py-2 rounded hover:bg-orange-600">
                        Order Now
                    </button>
                </div>
            </div>

            <!-- Card 6 -->
            <div class="bg-white rounded-lg shadow-md overflow-hidden">
                <img 
                    src="https://images.unsplash.com/photo-1579954115545-a95591f28bfc"
                    alt="Ice Cream"
                    class="w-full h-48 object-cover"
                >

                <div class="p-5">
                    <h3 class="text-xl font-bold text-gray-800">
                        Ice Cream
                    </h3>

                    <p class="text-gray-600 mt-2">
                        Creamy and refreshing ice cream
                        available in different flavors.
                    </p>

                    <button class="mt-4 bg-orange-500 text-white px-5 py-2 rounded hover:bg-orange-600">
                        Order Now
                    </button>
                </div>
            </div>

        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white text-center py-4">
        <p>© 2026 Food Menu | All Rights Reserved</p>
    </footer>

</body>
</html>
