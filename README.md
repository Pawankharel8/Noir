# Noir
Blog Site

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/style.css">
    <link href="images/fabicon.png" type="image" rel="icon">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css">
    <title>Noir</title>
    <style>  
     @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            list-style: none;
            text-decoration: none;
        }

        body {
            line-height: 1.5;
            font-family: 'Poppins', sans-serif;
        }

        header {
            width: 100%;
            height: 80px;
            border-bottom: 1px solid rgba(16, 16, 16, 0.1);
            display: flex;
            align-items: center;
            padding: 0 20px;
            background: #fff;
        }

        .inner {
            width: 100%;
            max-width: 1300px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin: 0 auto;
        }

        .logo img {
            height: 50px;
        }

        nav {
            display: flex;
            align-items: center;
        }

        nav li {
            margin: 0 15px;
        }

        nav a {
            color: #101010;
            font-weight: 500;
        }

        .button {
            background-color: #1ab26b;
            color: #FFF;
            padding: 10px 20px;
            border-radius: 4px;
            font-weight: 500;
        }

        .button:hover {
            filter: brightness(1.05);
        }

        .menu-toggle {
            display: none;
            font-size: 30px;
            cursor: pointer;
        }

        @media screen and (max-width: 768px) {
            nav {
                display: none;
                flex-direction: column;
                position: absolute;
                top: 80px;
                left: 0;
                width: 100%;
                background: white;
                padding: 10px 0;
                box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            }

            nav.active {
                display: flex;
            }

            nav li {
                text-align: center;
                margin: 10px 0;
            }

            .menu-toggle {
                display: block;
            }
        }
.container{
    max-width: 1170px;
    margin:auto;
}
.row{
    display: flex;
    flex-wrap: wrap;
}
ul{
    list-style: none;
}
.footer{
    background-color: #24262b;
    padding: 70px 0;
    width: 100%;
    position: absolute;
    bottom: 0;
    z-index: -1;
}
.footer-col{
   width: 25%;
   padding: 0 15px;
}
.footer-col h4{
    font-size: 18px;
    color: #ffffff;
    text-transform: capitalize;
    margin-bottom: 35px;
    font-weight: 500;
    position: relative;
}
.footer-col h4::before{
    content: " ";
    position: absolute;
    left:0;
    bottom: -10px;
    background: radial-gradient(circle, rgba(2,0,36,1) 0%, rgba(241,129,102,1) 100%, rgba(0,212,255,1) 100%);
    height: 2px;
    box-sizing: border-box;
    width: 50px;
}
.footer-col ul li:not(:last-child){
    margin-bottom: 10px;
}
.footer-col ul li a{
    font-size: 16px;
    text-transform: capitalize;
    color: #ffffff;
    text-decoration: none;
    font-weight: 300;
    color: #bbbbbb;
    display: block;
    transition: all 0.3s ease;
}
.footer-col ul li a:hover{
    color: #ffffff;
    padding-left: 8px;
}
.footer-col .social-links a{
    display: inline-block;
    height: 40px;
    width: 40px;
    background-color: rgba(255,255,255,0.2);
    margin:0 10px 10px 0;
    text-align: center;
    line-height: 40px;
    border-radius: 50%;
    color: #ffffff;
    transition: all 0.5s ease;
}
.footer-col .social-links a:hover{
    padding-left: 5px;
}
    </style>
</head>
<body>
    <header>
        <div class="inner">
            <div class="logo">
                <img src="images/logo.png" alt="Logo">
            </div>
            <div class="menu-toggle">&#9776;</div>
            <nav>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Contact</a></li>
                <li><a href="page2.html" class="button">LOGIN</a></li>
                <li><a href="page1.html" class="button">SIGN UP</a></li>
            </nav>
        </div>
    </header>
    <footer class="footer">
        <div class="container">
            <div class="row">
                <div class="footer-col">
                    <h4>Help</h4>
                    <ul>
                        <li><a href="#">Help center</a></li>
                        <li><a href="#">Help forum</a></li>
                        <li><a href="#">Video Tutorial</a></li>
                    </ul>
                </div>
                <div class="footer-col">
                    <h4>Group A</h4>
                    <ul>
                        <li><a href="#">Pawan kharel</a></li>
                        <li><a href="#">Roshni Tamang</a></li>
                        <li><a href="#">Samrat Thapa</a></li>
                        <li><a href="#">Mandip Libang</a></li>
                    </ul>
                </div>
                <div class="footer-col">
                    <h4>Made by</h4>
                    <ul>
                        <li><a href="#">Black Lineage</a></li>
                    </ul>
                </div>
                <div class="footer-col">
                    <h4>follow us</h4>
                    <div class="social-links">
                        <a href="#"><i class="fab fa-facebook-f"></i></a>
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                        <a href="#"><i class="fab fa-github"></i></a>
                    </div>
                </div>
            </div>
        </div>
   </footer>
    <script>
        document.querySelector(".menu-toggle").addEventListener("click", function() {
            document.querySelector("nav").classList.toggle("active");
        });
    </script>
</body>
</html>
