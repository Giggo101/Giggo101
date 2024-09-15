
/* Grundläggande stilar */
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f5f5f5;
    color: #333;
}

/* Header-styling */
header {
    background-color: #0a0a23;
    padding: 20px 0;
}

.container {
    width: 80%;
    margin: 0 auto;
}

.logo {
    color: white;
    text-align: center;
    font-size: 2rem;
    font-weight: bold;
}

nav ul {
    list-style: none;
    padding: 0;
    text-align: center;
}

nav ul li {
    display: inline-block;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 1.2rem;
}

nav ul li a:hover {
    color: #f4b400;
}

/* Produkter Sektion */
#produkter {
    padding: 50px 0;
    background-color: #fff;
}

#produkter h2 {
    text-align: center;
    font-size: 2rem;
    margin-bottom: 40px;
}

.product-grid {
    display: flex;
    justify-content: center;
    gap: 20px;
}

.product-item {
    text-align: center;
    background-color: #f0f0f0;
    padding: 20px;
    border-radius: 8px;
    width: 200px;
    transition: transform 0.3s ease;
}

.product-item img {
    width: 100%;
    height: auto;
    border-radius: 8px;
}

.product-item:hover {
    transform: translateY(-10px);
}

.product-item h3 {
    margin-top: 15px;
    font-size: 1.1rem;
}

/* Om Oss Sektion */
#omoss {
    padding: 50px 0;
    background-color: #e5e5e5;
    text-align: center;
}

#omoss h2 {
    font-size: 2rem;
    margin-bottom: 20px;
}

#omoss p {
    width: 60%;
    margin: 0 auto;
    font-size: 1.2rem;
    line-height: 1.5;
}

/* Kontakt Sektion */
#kontakt {
    padding: 50px 0;
    background-color: #fff;
}

#kontakt h2 {
    text-align: center;
    font-size: 2rem;
    margin-bottom: 20px;
}

form {
    width: 50%;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    gap: 15px;
}

input, textarea {
    padding: 10px;
    font-size: 1rem;
    border: 1px solid #ccc;
    border-radius: 5px;
}

button {
    padding: 10px 20px;
    font-size: 1rem;
    background-color: #0a0a23;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #f4b400;
}

/* Footer */
footer {
    text-align: center;
    padding: 20px 0;
    background-color: #0a0a23;
    color: white;
    margin-top: 50px;
}

