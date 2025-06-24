```html name=index.html
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Warung Tegal</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Warung Tegal</h1>
        <p>Makan Enak, Harga Bersahabat</p>
    </header>
    <main>
        <section class="menu">
            <h2>Daftar Menu</h2>
            <div class="menu-list">
                <div class="menu-item">
                    <img src="image1" alt="Bakso" />
                    <h3>Bakso</h3>
                    <p>Harga: Rp. 10.000 / mangkok</p>
                </div>
                <div class="menu-item">
                    <img src="https://img.freepik.com/free-photo/nasi-goreng-indonesian-cuisine_1150-11028.jpg?w=400" alt="Nasi Goreng" />
                    <h3>Nasi Goreng</h3>
                    <p>Harga: Rp. 12.000 / porsi</p>
                </div>
                <div class="menu-item">
                    <img src="https://img.freepik.com/free-photo/soto-ayam-indonesian-chicken-soup_1150-11111.jpg?w=400" alt="Soto Ayam" />
                    <h3>Soto Ayam</h3>
                    <p>Harga: Rp. 11.000 / mangkok</p>
                </div>
                <div class="menu-item">
                    <img src="https://img.freepik.com/free-photo/pecel-lele-indonesian-food_1150-11112.jpg?w=400" alt="Pecel Lele" />
                    <h3>Pecel Lele</h3>
                    <p>Harga: Rp. 13.000 / porsi</p>
                </div>
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 Warung Tegal. All rights reserved.</p>
    </footer>
</body>
</html>
```

```css name=styles.css
body {
    font-family: 'Segoe UI', Arial, sans-serif;
    margin: 0;
    padding: 0;
    background: #f6f6f6;
    color: #222;
}

header {
    background: #a5c956;
    color: #fff;
    padding: 24px 0 12px 0;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 2.4em;
}

header p {
    margin: 8px 0 0 0;
    font-size: 1.1em;
}

main {
    padding: 32px 8px;
    max-width: 900px;
    margin: 0 auto;
}

.menu {
    background: #fff;
    border-radius: 8px;
    padding: 24px;
    box-shadow: 0 2px 8px #0001;
}

.menu h2 {
    text-align: center;
    margin-bottom: 28px;
}

.menu-list {
    display: flex;
    flex-wrap: wrap;
    gap: 32px;
    justify-content: center;
}

.menu-item {
    width: 210px;
    background: #fafafa;
    border-radius: 8px;
    box-shadow: 0 1px 4px #0001;
    text-align: center;
    padding: 18px 8px 14px 8px;
    transition: transform 0.2s;
}
.menu-item:hover {
    transform: translateY(-5px) scale(1.04);
    box-shadow: 0 4px 12px #0002;
}

.menu-item img {
    width: 140px;
    height: 100px;
    object-fit: cover;
    border-radius: 6px;
    margin-bottom: 12px;
}

.menu-item h3 {
    margin: 0 0 8px 0;
    font-size: 1.15em;
}

footer {
    text-align: center;
    padding: 14px 0;
    background: #d7e7af;
    color: #4d4d4d;
    margin-top: 40px;
    font-size: 0.95em;
}
