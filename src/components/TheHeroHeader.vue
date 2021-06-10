<template>
    <main class="container">
        <img src="img/ReclikPiotr500x500.jpg" alt="author's photo" class="photo-author">

        <div class="title-container">
            <div class="line"></div>
                <div class="">
                    <h1 class="title">Piotr Żyła</h1>
                    <h3 class="subtitle">@preclson</h3>
                    <h3 class="subtitle">@reclikp</h3>
                </div>
            <div class="line"></div>
        </div>

        <div class="socials-container">
            <a href="#"><i class="icon-github fab fa-github"></i></a>
            <a href="#"><img src="img/iconfinder-fiverr-white.svg" alt="" class="icon-fiverr"></a>
            <a href="#"><i class="icon-contact fas fa-envelope"></i></a>
        </div>
    </main>
</template>

<script>
    export default {
        name: 'TheHeroHeader'
    }
</script>

<style lang="scss" scoped>
    .container {
        max-width: 100%;
        height: 100vh;
        
        background-color: #000000;
        background-image: url("https://www.transparenttextures.com/patterns/cartographer.png");
        //background-image: url("../../public/img/Stars.jpg");
        background-attachment: fixed;
        //background-position: center bottom;
        //background-repeat: no-repeat;
        //background-size: cover;

        display: flex;
        flex-direction: column;
        justify-content: center;

        text-align: center;
        z-index: -1;
        box-shadow: 0px 0px 15px 5px #000000;

        .title {
            font-size: 3rem;
            font-weight: 300;

            margin: 0;
            padding: 0;
        }

        .subtitle {
            font-size: 1.2rem;
            font-weight: 100;

            margin: 0;
            padding: 0;
        }

        
        .photo-author {
            width: 8%;
            border-radius: 50%;
            border: 2px solid #fff;
            align-self: center;
        }

        .title-container {
            display: flex;
            flex-direction: row;
            justify-content: space-evenly;
            align-items: center;

            margin-top: 3rem;
            .line {
                width: 30%;
                height: 0;
                border-top: 1px solid #fff;
                //border-bottom: .5px solid #fff;
            }

        }

        .socials-container {
            display: flex;
            justify-content: space-around;
            align-items: center;

            padding: 0 40%;
            margin-top: 5rem;

            a {
              color: #fff;  
            }

            .icon-github {
                font-size: 32px;
            }

            .icon-fiverr {
                width: 32px;
                height: auto;
            }

            .icon-contact {
                font-size: 32px;
            }
        }
    }
</style>