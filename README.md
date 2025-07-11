# Yogaya-Venture-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yogaya Venture - Customer Portal</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 font-sans">
    <!-- Header -->
    <header class="bg-indigo-600 text-white py-6">
        <div class="container mx-auto text-center">
            <h1 class="text-4xl font-bold">Yogaya Venture</h1>
            <p class="mt-2 text-lg">Empowering Wellness Through Yoga</p>
        </div>
    </header>

    <!-- Main Content -->
    <main class="container mx-auto py-12 px-4">
        <section class="max-w-md mx-auto bg-white p-8 rounded-lg shadow-lg">
            <h2 class="text-2xl font-semibold text-center text-gray-800 mb-6">Customer Login</h2>
            <form id="loginForm" onsubmit="handleLogin(event)">
                <div class="mb-4">
                    <label for="email" class="block text-gray-700 font-medium mb-2">Email</label>
                    <input type="email" id="email" name="email" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-indigo-500" required>
                </div>
                <div class="mb-6">
                    <label for="password" class="block text-gray-700 font-medium mb-2">Password</label>
                    <input type="password" id="password" name="password" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-indigo-500" required>
                </div>
                <button type="submit" class="w-full bg-indigo-600 text-white py-2 rounded-lg hover:bg-indigo-700 transition duration-300">Login</button>
            </form>
            <p class="mt-4 text-center text-gray-600">
                Don't have an account? <a href="#" class="text-indigo-600 hover:underline">Sign up</a>
            </p>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-6">
        <div class="container mx-auto text-center">
            <p>&copy; 2025 Yogaya Venture. All rights reserved.</p>
        </div>
    </footer>

    <script>
        function handleLogin(event) {
            event.preventDefault();
            const email = document.getElementById('email').value;
            const password = document.getElementById('password').value;
            // Placeholder for login logic
            alert(`Login attempt with Email: ${email}`);
            // Add actual authentication logic here
            document.getElementById('loginForm').reset();
        }
    </script>
</body>
</html>
