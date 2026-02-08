* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Inter', sans-serif;
}

body {
    background: #050509;
    color: #fff;
}

/* HEADER */
.top {
    position: fixed;
    top: 0;
    width: 100%;
    padding: 25px 80px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: linear-gradient(to bottom, #050509dd, transparent);
    z-index: 10;
}

.brand {
    font-size: 32px;
    font-weight: 800;
    letter-spacing: 6px;
    background: linear-gradient(90deg, #8b5cf6, #ec4899);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}

nav a {
    margin-left: 35px;
    text-decoration: none;
    color: #ccc;
    font-weight: 300;
}

nav a:hover {
    color: #fff;
}

/* HERO */
.hero {
    height: 100vh;
    background: url("https://images.unsplash.com/photo-1520975916090-3105956dac38") center/cover no-repeat;
    position: relative;
}

.overlay {
    position: absolute;
    inset: 0;
    background: linear-gradient(to bottom, #050509aa, #050509);
}

.hero-content {
    position: relative;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding-left: 80px;
}

.hero h1 {
    font-size: 88px;
    font-weight: 800;
}

.hero p {
    margin-top: 20px;
    font-size: 22px;
    opacity: 0.8;
}

.buttons {
    margin-top: 40px;
}

button {
    padding: 16px 40px;
    border-radius: 6px;
    font-weight: 600;
    cursor: pointer;
    border: none;
    margin-right: 20px;
}

.main {
    background: linear-gradient(90deg, #8b5cf6, #ec4899);
    color: white;
    box-shadow: 0 0 30px #8b5cf699;
}

.ghost {
    background: transparent;
    color: white;
    border: 1px solid #ffffff33;
}

/* STATS */
.stats {
    display: flex;
    justify-content: space-around;
    padding: 80px;
    background: #07070c;
}

.stat span {
    font-size: 48px;
    font-weight: 800;
    color: #8b5cf6;
}

.stat p {
    opacity: 0.7;
}

/* FOOTER */
footer {
    text-align: center;
    padding: 40px;
    opacity: 0.5;
}
