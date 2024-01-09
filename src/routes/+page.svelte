<div class="container">
    <div class="header">
        <h1 class="titolo">Portfolio Educazione Civica di Samuel Salvatore</h1>
        <hr>
        <h1 class="pres">Mi presento</h1>
    </div>

    <img id="piccolo" src="/piccolo.jpeg" alt="piccino">
    <p class="papiro text1">
        Sono Samuel Salvatore e ho terminato quest'anno la quinta informatica all'istituto agnelli. 
        Il mio percorso scolastico è iniziato con un anno di anticipo rispetto al previsto perché, essendo nato nel Gennaio 2006, i 
        miei genitori hanno deciso di farmi fare la primina.<br>Dopo aver frequentato le scuole elementari alla 'Gabbrio Casati' ed essere  
        uscito con otto decimi dalla scuola media 'Nigra' mi sono avventurato al liceo scientifico, scienze applicate, presso l'istituto 'Alessandro
        Volta'.
    </p> 
   
    <p class="papiro text2">
        Terminato il biennio, in seguito a una rivalutazione sulle mie passioni scolastiche, sono arrivato qua: un triennio ricco di 
        apprendimento e buona formazione.  Al di fuori della scuola pratico basket a livello agonistico, ormai da 7 anni, e frequento il gruppo
        MGS (Movimento Giovanile Salesiano), sia a scuola sia nell'oratorio San Paolo, con le diverse attività che vengono proposte.<br>
        La mia famiglia è composta da 10 persone: mamma, papà, 1 sorella maggiore, io, 1 sorella minore e 6 fratellini.
    </p>
    <img id="grande" src="/grande.jpeg" alt="grande">

    <img id="family" src="/family.jpg" alt="famiglia">
    <p class="papiro text3">
        I nomi di alcuni miei fratelli e il mio dicono molto di più di quanto sembri, infatti, sono spagnoli proprio per la nostra origine.
        Questo è un ...
    </p>
</div>

<style>
    .container {
        display: grid;
        grid-template-rows: auto;
        grid-template-columns: 30% 40% 30%;
        grid-template-areas: 
        "header header header"
        "img1 text1 text1"
        "text2 text2 img2"
        "img3 text3 text3";
        margin-right: 1.5%;
    }

    .header {
        grid-area: header;
    }

    .titolo {
        font-size: 3.5vw;
        font-family: 'Dancing Script', cursive;
        text-align: center;    
        color: red;
        text-shadow: 1px 1px black;
    }

    .pres {
        font-size: 2.5vw;
        font-family: 'Dancing Script', cursive;
        text-align: center;    
        color: red;
        text-shadow: 1px 1px black;
    }

    #piccolo {
        border-radius: 15px 0px 0px 0px;
        border: 5px inset rgb(114, 104, 104);
        grid-area: img1;
        width: 89%;
        margin-left: 11%;
        height: auto;
    }

    .papiro {
        line-height: 180%;
        margin: 2%;
        text-align: justify;
        font-family: Georgia, 'Times New Roman', Times, serif;
        font-size: 1.3vw;
        width: 90%;
        margin: auto;
    }

    .text1 {
        grid-area: text1;
    }

    .text2 {
        grid-area: text2;
    }

    .text3 {
        grid-area: text3;
    }

    #grande {
        margin-top: -3%;
        border-radius: 0px 0px 15px 0px;
        border: 5px outset rgb(114, 104, 104);
        grid-area: img2;
        width: 89%;
        height: auto;
    }

    #family {
        margin: auto;
        width: 25%;
        border-radius: 15px 0px 0px 0px;
        border: 5px inset rgb(114, 104, 104);
        grid-area: img3;
        margin-top: -8.5%;
        width: 89%;
        margin-left: 11%;
        height: auto;
    }
</style>