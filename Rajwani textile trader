<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Textile Machinery Hub - Buy & Sell</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
        header { background: #333; color: white; padding: 1rem; text-align: center; }
        .hero { background: url('machinery-banner.jpg') no-repeat center/cover; height: 400px; display: flex; align-items: center; justify-content: center; color: white; }
        .search { margin: 2rem; text-align: center; }
        .listings { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 1rem; padding: 2rem; }
        .item { border: 1px solid #ddd; padding: 1rem; }
        footer { background: #333; color: white; text-align: center; padding: 1rem; }
    </style>
</head>
<body>
    <header>
        <h1>Textile Machinery Hub</h1>
        <nav><a href="#listings">Browse</a> | <a href="#contact">Contact</a></nav>
    </header>
    <section class="hero">
        <div>
            <h2>Buy & Sell Textile Machinery</h2>
            <p>Find looms, spinners, and more from trusted sellers.</p>
        </div>
    </section>
    <section class="search">
        <input type="text" placeholder="Search machinery..." id="search">
        <button onclick="searchItems()">Search</button>
    </section>
    <section id="listings" class="listings">
        <!-- Dynamic listings would be loaded via JS/API -->
        <div class="item">
            <img src="loom.jpg" alt="Shuttle Loom" width="100%">
            <h3>Used Shuttle Loom</h3>
            <p>$5,000 - Excellent condition</p>
            <button>Contact Seller</button>
        </div>
        <!-- Add more items -->
    </section>
    <footer>
        <p>&copy; 2023 Textile Machinery Hub. All rights reserved.</p>
    </footer>
    <script>
        function searchItems() {
            // Basic JS for search; expand with backend
            const query = document.getElementById('search').value.toLowerCase();
            const items = document.querySelectorAll('.item');
            items.forEach(item => {
                item.style.display = item.textContent.toLowerCase().includes(query) ? 'block' : 'none';
            });
        }
    </script>
</body>
</html>
