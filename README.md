<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Mother's Day!</title>
    <!-- Tailwind CSS CDN for easy styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Custom styles for a more personal touch */
        body {
            font-family: 'Inter', sans-serif; /* Using Inter font as requested */
            background-color: #fce4ec; /* Light pink background */
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh; /* Ensure it takes full viewport height */
            margin: 0;
            padding: 20px; /* Add some padding for smaller screens */
            box-sizing: border-box; /* Include padding in element's total width and height */
        }
        .card {
            background-color: #ffffff; /* White card background */
            border-radius: 1.5rem; /* More rounded corners */
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04); /* Soft shadow */
            padding: 2.5rem; /* Increased padding */
            text-align: center;
            max-width: 600px; /* Max width for readability */
            width: 100%; /* Make it fluid */
            color: #4a4a4a; /* Darker text color */
            position: relative; /* For the heart icon positioning */
        }
        .heart-icon {
            color: #e91e63; /* Pink heart color */
            font-size: 3rem; /* Larger heart icon */
            margin-bottom: 1.5rem; /* Space below the icon */
            animation: pulse 1.5s infinite; /* Simple pulse animation */
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
        .title {
            font-size: 2.5rem; /* Larger title */
            font-weight: 700; /* Bold title */
            color: #d81b60; /* Dark pink for title */
            margin-bottom: 1rem;
        }
        .message {
            font-size: 1.25rem; /* Readable message font size */
            line-height: 1.75; /* Good line height for readability */
            margin-bottom: 2rem;
        }
        .signature {
            font-size: 1.1rem; /* Signature font size */
            font-style: italic;
            color: #757575; /* Lighter color for signature */
        }

        /* Responsive adjustments using Tailwind's breakpoints */
        @media (min-width: 640px) { /* sm breakpoint */
            .card {
                padding: 3rem;
            }
            .title {
                font-size: 3rem;
            }
            .message {
                font-size: 1.35rem;
            }
        }
        @media (min-width: 768px) { /* md breakpoint */
            .card {
                padding: 4rem;
            }
            .title {
                font-size: 3.5rem;
            }
            .message {
                font-size: 1.5rem;
            }
        }
    </style>
</head>
<body>
    <div class="card">
        <!-- Heart icon using SVG for better scalability and styling -->
        <svg class="heart-icon mx-auto" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor">
            <path d="M12 21.35l-1.45-1.32C5.4 15.36 2 12.28 2 8.5 2 5.42 4.42 3 7.5 3c1.74 0 3.41.81 4.5 2.09C13.09 3.81 14.76 3 16.5 3 19.58 3 22 5.42 22 8.5c0 3.78-3.4 6.86-8.55 11.54L12 21.35z"/>
        </svg>
        <h1 class="title">Happy Mother's Day!</h1>
        <p class="message">
            To the most wonderful mom in the world, your love is a constant source of strength, joy, and inspiration. Thank you for your endless sacrifices, your unwavering support, and for always believing in me. Every day is a gift because of you.
            <br><br>
            Wishing you a day filled with all the happiness you bring into our lives. You deserve all the love and appreciation today and always!
        </p>
        <p class="signature">- Your Lovely Son</p>
    </div>
</body>
</html>
