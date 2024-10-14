<html>
<head>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"></link>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
        }
    </style>
</head>
<body class="bg-blue-900 flex items-center justify-center min-h-screen">
    <div class="bg-white rounded-t-lg shadow-lg w-80">
        <div class="flex flex-col items-center p-6">
            <div class="bg-gray-200 rounded-full w-20 h-20 flex items-center justify-center mb-4">
                <i class="fas fa-user text-gray-400 text-4xl"></i>
            </div>
            <h2 class="text-gray-600 text-xl mb-2">Hello</h2>
            <p class="text-gray-400 text-sm">Register to create new your account</p>
        </div>
    </div>
    <div class="bg-blue-900 rounded-b-lg shadow-lg w-80 p-6">
        <div class="flex justify-between mb-4">
            <button class="text-gray-400">Sign In</button>
            <button class="text-white border-b-2 border-yellow-500">Sign Up</button>
        </div>
        <div class="space-y-4">
            <input type="email" placeholder="Email" class="w-full p-3 rounded-full bg-yellow-100 text-gray-700 focus:outline-none">
            <input type="password" placeholder="Password" class="w-full p-3 rounded-full bg-yellow-100 text-gray-700 focus:outline-none">
        </div>
        <button class="w-full mt-6 p-3 rounded-full bg-yellow-500 text-white font-bold">Sign Up</button>
        <p class="text-center text-gray-400 mt-4">Reset My Password</p>
    </div>
</body>
</html> 
