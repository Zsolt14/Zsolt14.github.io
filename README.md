# Zsolt14.github.io
<!DOCTYPE html>
<html lang="hu">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fitness Website</title>
    <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
    <section>
        <header>
            <a href="#" class="logo">Zsolt 14</a>
            <div class="toggleMenu" onclick="toggleMenu();"></div>
            <ul class="navigation">
                <li><a href="#">services</a></li>
                <li><a href="#">about</a></li>
                <li><a href="#">hire me</a></li>
            </ul>
        </header>
        <div class="content">
            <div class="contentBx">
                <h2>Build Perfect Body</br>With Clean Mind</h2>
                <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the
                    industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type
                    and scrambled it to make a type specimen book.</p>
                <a href="#">Get Started</a>
            </div>
        </div>
    </section>
    <script type="text/javascript">
        function toggleMenu() {
            const toggleMenu = document.querySelector('.toggleMenu');
            const navigation = document.querySelector('.navigation');
            toggleMenu.classList.toggle('active');
            navigation.classList.toggle('active');
        }
    </script>
</body>

</html>
