<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OMG Makeup - Luxury Glam</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            text-align: center;
            background: linear-gradient(135deg, #5c0f2e, #2e1a47, #1f1b2e);
            color: white;
            margin: 0;
            padding: 20px;
            overflow-x: hidden;
        }

        .container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            max-width: 1200px;
            margin: auto;
            gap: 20px;
            overflow-x: auto; /* allows horizontal scroll if needed */
        }

        h1 {
            font-size: 42px;
            font-weight: bold;
            background: linear-gradient(90deg, #9d005d, #ff5c8f);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        p {
            font-size: 18px;
            color: #ff5c8f;
        }

        /* Navbar Pencarian */
        .navbar {
            display: flex;
            justify-content: center;
            padding: 15px 0;
            background: rgba(0, 0, 0, 0.6);
            margin-bottom: 30px;
            border-radius: 50px;
        }

        .navbar input[type="text"] {
            padding: 12px;
            font-size: 16px;
            width: 70%;
            max-width: 600px;
            border: none;
            border-radius: 30px;
            margin-right: 10px;
        }

        .navbar button {
            padding: 12px 20px;
            font-size: 16px;
            background: #9d005d;
            color: white;
            border: none;
            border-radius: 30px;
            cursor: pointer;
            transition: 0.3s;
        }

        .navbar button:hover {
            background: #ff5c8f;
            transform: scale(1.05);
        }

        .product {
            display: flex;
            flex-direction: column;
            align-items: center;
            background: rgba(255, 255, 255, 0.1);
            border: 2px solid rgba(255, 92, 143, 0.7);
            border-radius: 20px;
            padding: 20px;
            box-shadow: 0 8px 15px rgba(255, 92, 143, 0.4);
            width: 260px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            position: relative;
        }

        .product:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(255, 92, 143, 0.7);
        }

        .product img {
            width: 140px;
            height: 140px;
            border-radius: 15px;
            object-fit: cover;
            margin-bottom: 10px;
            border: 3px solid #ff5c8f;
        }

        .discount {
            position: absolute;
            top: 10px;
            left: 10px;
            background: red;
            color: white;
            padding: 5px 10px;
            font-size: 14px;
            font-weight: bold;
            border-radius: 5px;
        }

        .product-info {
            text-align: center;
        }

        .product-info p {
            margin: 5px 0;
            font-size: 16px;
            color: white;
        }

        .product-info p:last-child {
            font-weight: bold;
            color: #ff5c8f;
        }

        .product a {
            text-decoration: none;
            background: linear-gradient(90deg, #9d005d, #ff5c8f);
            color: white;
            padding: 12px;
            border-radius: 10px;
            font-weight: bold;
            display: inline-block;
            margin-top: 10px;
            transition: background 0.3s, transform 0.2s ease;
        }

        .product a:hover {
            transform: scale(1.05);
        }

        .whatsapp {
            margin-top: 20px;
            padding: 15px;
            background: #25D366;
            color: white;
            display: inline-block;
            text-decoration: none;
            border-radius: 10px;
            font-weight: bold;
            transition: background 0.3s, transform 0.2s;
        }

        .whatsapp:hover {
            background: #1ebe57;
            transform: scale(1.1);
        }
    </style>
</head>
<body>
    <!-- Navbar Pencarian -->
    <div class="navbar">
        <input type="text" id="search" placeholder="Cari produk...">
        <button onclick="searchProduct()">Cari</button>
    </div>

    <h1>OMG Makeup - Luxury Glam</h1>
    <p>Tampil Memukau, Percaya Diri Setiap Saat!✨💄</p>
    <div class="container">
        <div class="product">
            <div class="discount">-5%</div>
            <img src="ombre.jpg" alt="Lip Cream OMG">
            <div class="product-info">
                <p>OMG OH MY GLAM Mattelast Lip Cream</p>
                <p>Rp27.500</p>
            </div>
            <a href="https://s.shopee.co.id/7fKxrRZNYH" target="_blank">Beli Sekarang</a>
        </div>

        <div class="product">
            <div class="discount">-5%</div>
            <img src="cushion.jpg" alt="Cushion OMG">
            <div class="product-info">
                <p>OMG Flawless Cushion</p>
                <p>Rp62.125</p>
            </div>
            <a href="https://s.shopee.co.id/1VkKTd5Zuy" target="_blank">Beli Sekarang</a>
        </div>

        <div class="product">
            <div class="discount">-3%</div>
            <img src="mascara.jpg" alt="Eyeliner OMG">
            <div class="product-info">
                <p>OMG Oh My Glam Lashtention Waterproof Mascara</p>
                <p>Rp34.920</p>
            </div>
            <a href="https://s.shopee.co.id/1qNAsKKMz4" target="_blank">Beli Sekarang</a>
        </div>

        <div class="product">
            <div class="discount">-20%</div>
            <img src="blushon.jpeg" alt="Blush On OMG">
            <div class="product-info">
                <p>OMG OH MY GLAM Eye Studio Palette</p>
                <p>Rp58.000</p>
            </div>
            <a href="https://shopee.co.id/OMG-OH-MY-GLAM-Eye-Studio-Palette-9-Shades-Eyeshadow-Palette-High-Pigment-And-Smooth-Powder-Long-Lasting-Easy-to-Blend-Glitter-Highlighter-Contour-Make-Up-Warna-Lengkap-Nude-Coklat-Pink-i.401724234.25083983400" target="_blank">Beli Sekarang</a>
        </div>

        <div class="product">
            <div class="discount">-5%</div>
            <img src="sunscreenn.jpg" alt="Highlighter OMG">
            <div class="product-info">
                <p>OMG Oh My Glow Bright Booster UV</p>
                <p>Rp26.600</p>
            </div>
            <a href="https://s.shopee.co.id/vWizXIvn" target="_blank">Beli Sekarang</a>
        </div>

        <div class="product">
            <div class="discount">-3%</div>
            <img src="lipglos.jpg" alt="Lip Gloss OMG">
            <div class="product-info">
                <p>OMG Lip Gloss - Shiny Finish</p>
                <p>Rp26.675</p>
            </div>
            <a href="https://s.shopee.co.id/2B01J01lh5" target="_blank">Beli Sekarang</a>
        </div>

        <!-- Additional Products -->
        <div class="product">
            <div class="discount">-3%</div>
            <img src="fundation.jpg" alt="OMG Foundation">
            <div class="product-info">
                <p>OMG Oh My Glam Coverlast Liquid Foundation </p>
                <p>Rp32.500</p>
            </div>
            <a href="https://s.shopee.co.id/20gbBc7p0i" target="_blank">Beli Sekarang</a>
        </div>

        <div class="product">
            <div class="discount">-29%</div>
            <img src="eyebrow.jpg" alt="Eyebrow Pencil OMG">
            <div class="product-info">
                <p>OMG Eyebrow Pencil</p>
                <p>Rp25.000</p>
            </div>
            <a href="https://s.shopee.co.id/AKLj6xs3zp" target="_blank">Beli Sekarang</a>
        </div>

        <div class="product">
            <div class="discount">-5%</div>
            <img src="two cake.jpg" alt="OMG Tow Way Cake">
            <div class="product-info">
                <p>OMG Oh My Glam Coverlast Two Way Cake</p>
                <p>Rp28.500</p>
            </div>
            <a href="https://s.shopee.co.id/1qNAzQE5I0" target="_blank">Beli Sekarang</a>
        </div>

        <div class="product">
            <div class="discount">-49%</div>
            <img src="panthenol.jpg" alt="OMG Setting Spray">
            <div class="product-info">
                <p>OMG Oh My Glow Panthenol + Ceramide Moisture</p>
                <p>Rp36.000</p>
            </div>
            <a href="https://s.shopee.co.id/vWo4ybJo" target="_blank">Beli Sekarang</a>
        </div>

    </div>

    <a class="whatsapp" href="https://wa.me/6285713128866" target="_blank">Hubungi via WhatsApp</a>

    <script>
        function searchProduct() {
            let query = document.getElementById('search').value.toLowerCase();
            let products = document.querySelectorAll('.product');
            
            products.forEach(product => {
                let productName = product.querySelector('.product-info p').textContent.toLowerCase();
                if (productName.includes(query)) {
                    product.style.display = 'block';
                } else {
                    product.style.display = 'none';
                }
            });
        }
    </script>
</body>
</html>
