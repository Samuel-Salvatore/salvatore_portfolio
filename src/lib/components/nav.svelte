<svelte:head>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script&display=swap" rel="stylesheet">    
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200"/>
</svelte:head>

<nav class="barra">
    <img id="logo" src="/favicon.jpg" alt="logo">

    <h1 class="nav_titolo">Il mio triennio nell'istituto Agnelli</h1>

    <ul>
        <div class="bottone" id="icona"><a href="/"><li><span class="material-symbols-outlined">home</span></li></a></div>
        <div class="bottone"><a href="/anno1"><li>2021/2022</li></a></div>
        <div class="bottone"><a href="/anno2"><li>2022/2023</li></a></div>
        <div class="bottone"><a href="/anno3"><li>2023/2024</li></a></div>
    </ul>
</nav>


<style>
    nav {
        display: flex;
        flex-wrap: wrap;
        border: 1px solid black;
        border-radius: 15px;
        position: sticky;
        top: 5px;
        width: 100%;
        height: auto;
        background-color: aliceblue;
    }

    #logo {
        width: 15%;
        height: auto;
        border-radius: 15px;
    }

    a {
        text-decoration: none;
    }

    .nav_titolo {
        font-size: 1.9vw;
        font-family: 'Dancing Script', cursive;
        margin-left: 3%;
        line-height: 200%;
        color: red;
    }
        
    ul {
        list-style-type: none;
        width: 55%;
        display: flex;
        justify-content: space-evenly;
        align-items: center;
        font-size: 1.2vw;
    }

    .bottone {
        background-color: rgb(215, 62, 62);
        border-radius: 15px;
        text-align: center;
        line-height: 250%;
        width: 10rem;
        font-weight: bold;
    }

    .bottone a {
        color: white;
        font-size: 1vw;
    }

    #icona {
        width: 5rem;
    }

    .material-symbols-outlined{
        vertical-align: -30%;
    }

    .bottone:hover {
        background-color: white;
        transition: all 0.8s ease 0s;
        border: 1px solid red;
    }   

    .bottone:hover a {
        color: red;
        transition: all 0.5s ease 0s;
    }
</style>