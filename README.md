# BitMarket_New_style.css
body {
    font-family: sans-serif;
    background-color: black;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px;
    margin-bottom: 20px;
}

.button {
    background-color: #36bbce;
    color: black;
    text-decoration: none;
    padding: 15px;
    font-size: 24px;
    border-radius: 10px;
    display: block;
}

.button:hover {
    background-color: blueviolet;
    color: whitesmoke;
    text-decoration: none;
    padding: 15px;
    font-size: 24px;
    border-radius: 10px;
    display: block;
}

nav {
    border-top: 5px solid white;
    border-bottom: 5px solid white;
    padding: 25px 100px 25px 95px;
    display: flex;
    justify-content: space-between;
}

.nav-link {
    font-size: 24px;
    color: white;
    text-decoration: none;
    display: block;
}

.nav-link:hover {
    font-size: 24px;
    color: lightblue;
    text-decoration: none;
    display: block;
}

h1 {
    text-align: center;
    color: white;
    font-size: 36px;
    margin-top: 45px;
    margin-bottom: 40px;
}

h1::before {
    content: url(https://mars.algoritmika.org/uploads/2021/03/Rectangle1_0_1616084234.svg);
    color: white;
    height: 50px;
    width: 50px;
}

h1::after {
    content: url(https://mars.algoritmika.org/uploads/2021/03/Rectangle1_0_1616084234.svg);
    color: white;
    height: 50px;
    width: 50px;
}

.post-text {
    font-size: 24px;
}

.info {
    display: flex;
    flex-wrap: wrap;
    max-width: 1100px;
    margin: 0 auto;
}

.post {
    background-color: white;
    padding: 15px 45px 30px 45px;
    width: 400px;
    margin: 20px;
    position: relative;
}

.article-but {
    text-decoration: none;
    background-color: #133aac;
    color: white;
    font-size: 24px;
    text-align: center;
    padding: 10px 75px 10px 75px;
    display: block;
}

.article-but:hover {
    text-decoration: none;
    background-color: white;
    color: #133aac;
    border: 2px solid #133aac;
    font-size: 24px;
    text-align: center;
    padding: 10px 75px 10px 75px;
    display: block;
}

.social {
    display: block;
    width: 30px;
}

footer {
    background-color: white;
    display: flex;
    justify-content: flex-start;
    align-items: center;
    padding: 30px 30px 20px 45px;
}

.footer-text {
    font-size: 24px;
    margin-right: 30px;
}

.footer-text span {
    color: #850AE5;
    font-weight: bolder;
}

.sot_set {
    position: fixed;
    padding: 5px;
    left: 660px;
    top: 230px;
    background-color: darkviolet;
    border: 1px solid darkviolet;
    border-radius: 3px;
}

.sot_set p {
    color: white;
    padding: 5px;
}

.post_2 {
    background-color: white;
    padding: 15px 45px 30px 45px;
    width: 400px;
    margin: 20px;
    position: relative;
}

.post_2 p {
    color: black;
}

.img_1 {
    position: absolute;
    top: 70px;
    right: 2px;
}

.tel::before {
    content: url("https://mars.algoritmika.org/uploads/2021/03/tel_0_1616091817.svg");
    width: 20px;
    height: 20px;
    display: inline-block;
}

.address::before {
    content: url("https://mars.algoritmika.org/uploads/2021/03/tel_0_1616091817.svg");
    width: 20px;
    height: 20px;
    display: inline-block;
    margin-right:5px;
}

.post_2:hover {
    background-color: lightblue;
    padding: 15px 45px 30px 45px;
    width: 400px;
    margin: 20px;
    position: relative;
}

.post:hover {
    background-color: lightblue;
    padding: 15px 45px 30px 45px;
    width: 400px;
    margin: 20px;
    position: relative;
}

h2:hover {
    color: white;
}

.social:hover {
    border-bottom: 3px double orange;
}

.text_for_sot_set:hover {
    color: orange;
    margin-top: 60px;
}
