<template>
    <div class="filmContainer">
        <div class="filmContent">
            <img class="filmImg" src="/f1themovie.jpg">
                <div class="filmInfo">
                <h1 class="movieTitle">F1 the movie</h1>
                <p class="timeLabel">Showing today at 1:00 PM</p>
                <p class="zaalInfo">Zaal 1</p>
                <p class="filmDuur">Duration: 2 hours 35 minutes</p>
            </div>
        </div>

        <div class="filmContent">
            <img class="filmImg" src="/minecraftthemovie.jpg">
                <div class="filmInfo">
                <h1 class="movieTitle">Minecraft the movie</h1>
                <p class="timeLabel">Showing today at 4:00 PM</p>
                <p class="zaalInfo">Zaal 1</p>
                <p class="filmDuur">Duration: 1 hour and 41 mintues</p>
            </div>
        </div>

    </div>

</template>

<style>

    .filmContainer {
        background: #F6F6F6;
        display: flex;
        width: 60rem;
        height: auto;
        margin: 20px;
        border-radius: 20px;
    }

    .filmContent {
        display: flex;
        background: #ffffff;
        margin: 2rem;
        width: 30rem;
        height: 100px;
        border-radius: 20px;
        overflow-y: hidden;
    }

    .filmInfo {
         margin-left: 0.25rem;
    }

     .filmImg {
        width: auto;
        height: 100%;
    }

    .movieTitle {
        color: #000;
        font-size: 1.5rem;
        font-weight: 600;
    }

    .timeLabel {
        color: #000;
        font-size: 0.75rem;
        font-style: italic;
    }

    .zaalInfo {
        color: #000;
        font-size: 0.75rem;
    }

    .filmDuur {
        color: #000;
        font-size: 0.75rem;
        
    }

</style>