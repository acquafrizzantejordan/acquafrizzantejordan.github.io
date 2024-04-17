Nike Jordan Evolution
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jordan Shoe Collection</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/github-markdown-css/4.0.0/github-markdown.min.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Ahorni&display=swap">
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        .header {
            text-align: center;
            font-size: 28px; /* Changed font size to 28px */
            margin-top: 20px;
            font-family: 'Ahorni', sans-serif; /* Changed font family to Ahorni */
            text-transform: uppercase; /* Ensures uppercase */
        }
        .tabs {
            display: flex;
            justify-content: center;
            margin-top: 20px;
        }
        .tab {
            padding: 10px; /* Adjusted padding */
            border: 2px solid #000; /* Border for basketball outline */
            cursor: pointer;
            margin: 0 5px;
            border-radius: 50%; /* Rounded shape */
            width: 30px; /* Set width and height */
            height: 30px; /* Set width and height */
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .tab-content {
            display: none;
            margin-top: 20px;
        }
        .tab-content.active {
            display: block;
        }
        .tab-content img {
            max-width: 100%; /* Ensure image fits within tab-content */
            height: auto; /* Maintain aspect ratio */
        }
    </style>
</head>
<body>
    <div class="header">JORDAN</div> <!-- Changed "Jordan" to uppercase -->
    <div class="tabs">
        <div class="tab" onclick="showTab(1)"></div> <!-- Empty div for basketball outline -->
        <div class="tab" onclick="showTab(2)"></div>
        <div class="tab" onclick="showTab(3)"></div>
        <div class="tab" onclick="showTab(4)"></div>
        <div class="tab" onclick="showTab(5)"></div>
        <div class="tab" onclick="showTab(6)"></div>
        <div class="tab" onclick="showTab(7)"></div>
        <div class="tab" onclick="showTab(8)"></div>
        <div class="tab" onclick="showTab(9)"></div>
        <div class="tab" onclick="showTab(10)"></div>
        <div class="tab" onclick="showTab(11)"></div>
        <div class="tab" onclick="showTab(12)"></div>
        <div class="tab" onclick="showTab(13)"></div>
    </div>
    
    <!-- Air Jordan 1 -->
    <div id="tab1" class="tab-content">
        <h2>Air Jordan 1</h2>
        <![Image 1](https://github.com/acquafrizzantejordan/acquafrizzantejordan.github.io/assets/145576039/b159e4c6-e7a3-4b2d-a156-fb16a0d89a8b)> <!-- Placeholder image, replace with actual Jordan 1 image -->
        <p>The Air Jordan 1 was first released in 1985. It was designed by Peter Moore and was the first signature shoe for Michael Jordan. It was published on the 1. April 1985 and took over the world rapidly. However did Michel Jordan himself complain about the shoe because it creased to slow. Therfore Micheal Jordan stated that the Air Jordan 1 doesn't perform well on court because it stops him from jumping correctly. Abother fact which is intresting about the Nike Air Jordan 1 is that it is indeed a very popular skateboarding shoe. </p>
    </div>
    
    <!-- Air Jordan 2 -->
    <div id="tab2" class="tab-content">
        <h2>Air Jordan 2</h2>
        <img src="jordan2.jpg" alt="Jordan 2 Image"> <!-- Placeholder image, replace with actual Jordan 2 image -->
        <p>The Air Jordan 2 was released in 1986. It was designed by Bruce Kilgore and introduced luxurious design elements.</p>
    </div>

    <!-- Repeat similar tab-content divs for Jordan 3 to Jordan 13 -->

    <script>
        function showTab(tabIndex) {
            var tabs = document.querySelectorAll('.tab-content');
            for (var i = 0; i < tabs.length; i++) {
                tabs[i].style.display = 'none';
            }
            document.getElementById('tab' + tabIndex).style.display = 'block';
        }
    </script>
</body>
</html>
