<template>
    <header>
        <div class="container">
            <nav>
                <ul class="menu">
                    <li class="logo">
                        <a href="#">
                            <img src="../../public/img/dc-logo.png" alt="">
                        </a>
                    </li>
                    <li><a href="#">CHARACTERS</a></li>
                    <li><a href="#">COMICS</a></li>
                    <li><a href="#">MOVIES</a></li>
                    <li><a href="#">TV</a></li>
                    <li><a href="#">GAMES</a></li>
                    <li><a href="#">COLLECTIBLES</a></li>
                    <li><a href="#">VIDEOS</a></li>
                    <li><a href="#">FANS</a></li>
                    <li><a href="#">NEWS</a></li>
                    <li><a href="#">SHOP</a></li>
                </ul>
            </nav>
        </div>
    </header>
</template>
  
<style>
header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 16px;
}

.logo {
    margin-right: 100px;
}

.logo img {
    height: 80px;
}

nav {
    display: flex;
    align-items: center;
    flex: 1;
    padding: 20px;
}

nav ul {
    display: flex;
    align-items: center;
    margin: 0;
    padding: 0;
    list-style-type: none;
    justify-content: flex-end;
    flex: 1;
}

nav li {
    margin-right: 32px;
}

nav a {
    color: grey;
    font-weight: bold;
    text-decoration: none;
}

@media screen and (max-width: 600px) {
    .logo {
        margin-right: 16px;
    }

    nav li {
        margin-right: 16px;
    }
}
</style>
  