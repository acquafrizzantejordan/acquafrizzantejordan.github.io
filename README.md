<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jordan Shoe Collection</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/github-markdown-css/4.0.0/github-markdown.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        .header {
            text-align: center;
            font-size: 36px;
            margin-top: 20px;
        }
        .tabs {
            display: flex;
            justify-content: center;
            margin-top: 20px;
        }
        .tab {
            padding: 10px 20px;
            background-color: #f0f0f0;
            border: 1px solid #ccc;
            cursor: pointer;
            margin: 0 5px;
        }
        .tab-content {
            display: none;
            margin-top: 20px;
        }
        .tab-content.active {
            display: block;
        }
    </style>
</head>
<body>
    <div class="header">Jordan</div>
    <div class="tabs">
        <div class="tab" onclick="showTab(1)">Jordan 1</div>
        <div class="tab" onclick="showTab(2)">Jordan 2</div>
        <div class="tab" onclick="showTab(3)">Jordan 3</div>
        <div class="tab" onclick="showTab(4)">Jordan 4</div>
        <div class="tab" onclick="showTab(5)">Jordan 5</div>
        <div class="tab" onclick="showTab(6)">Jordan 6</div>
        <div class="tab" onclick="showTab(7)">Jordan 7</div>
        <div class="tab" onclick="showTab(8)">Jordan 8</div>
        <div class="tab" onclick="showTab(9)">Jordan 9</div>
        <div class="tab" onclick="showTab(10)">Jordan 10</div>
        <div class="tab" onclick="showTab(11)">Jordan 11</div>
        <div class="tab" onclick="showTab(12)">Jordan 12</div>
        <div class="tab" onclick="showTab(13)">Jordan 13</div>
    </div>
    
    <!-- Jordan 1 -->
    <div id="tab1" class="tab-content">
        <h2>Jordan 1</h2>
        <p>The Air Jordan 1 was first released in 1985. It was designed by Peter Moore and was the first signature shoe for Michael Jordan.</p>
    </div>
    
    <!-- Jordan 2 -->
    <div id="tab2" class="tab-content">
        <h2>Jordan 2</h2>
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
