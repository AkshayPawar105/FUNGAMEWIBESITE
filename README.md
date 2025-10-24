# FUNGAMEWIBESITE
Made by Akshay &amp; Ashaaz 9th class students 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Fun Game by Akshay and Ashaaz</title>
<style>
    body {
        margin: 0;
        font-family: 'Poppins', sans-serif;
        background: linear-gradient(135deg, #8ec5fc, #e0c3fc);
        color: #333;
    }
    header {
        text-align: center;
        padding: 50px 20px 30px 20px;
        background: #6a11cb;
        color: white;
        border-bottom-left-radius: 30px;
        border-bottom-right-radius: 30px;
        box-shadow: 0 4px 20px rgba(0,0,0,0.2);
    }
    header h1 {
        margin: 0;
        font-size: 2.2rem;
    }
    header p {
        margin-top: 10px;
        font-size: 1.2rem;
        font-weight: 500;
    }
    .section {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        padding: 40px 20px;
        gap: 30px;
    }
    .card {
        background: white;
        border-radius: 20px;
        width: 220px;
        height: 150px;
        display: flex;
        justify-content: center;
        align-items: center;
        text-align: center;
        font-weight: bold;
        font-size: 1.2rem;
        color: #6a11cb;
        cursor: pointer;
        box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        transition: 0.3s;
    }
    .card:hover {
        transform: translateY(-10px);
        background: #f0e6ff;
        box-shadow: 0 8px 25px rgba(0,0,0,0.3);
    }
    footer {
        text-align: center;
        padding: 20px;
        background: #6a11cb;
        color: white;
        margin-top: 50px;
    }
    @media(max-width: 600px){
        .card {
            width: 80%;
            height: 120px;
        }
    }
</style>
</head>
<body>

<header>
    <h1>Fun Game by Akshay and Ashaaz</h1>
    <p>Play • Learn • Improve</p>
</header>

<section class="section">
    <div class="card" onclick="openCalculator()">Calculator 🧮</div>
    <div class="card" onclick="alert('Tic-Tac-Toe coming soon!')">Tic-Tac-Toe 🎮</div>
    <div class="card" onclick="alert('Puzzle Game coming soon!')">Puzzle 🧩</div>
    <div class="card" onclick="alert('Quiz Game coming soon!')">Math Quiz 🧠</div>
</section>

<footer>
    &copy; 2025 Fun Game by Akshay and Ashaaz | All rights reserved
</footer>

<script>
function openCalculator() {
    // opens calculator page in a new tab
    window.open('calculator.html', '_blank');
}
</script>

</body>
</html>
