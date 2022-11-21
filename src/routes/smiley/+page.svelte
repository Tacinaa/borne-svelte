<script lang="ts">

    let question = "Quelle est votre satisfaction globale au regard de l’accueil qui vous a été réservé ?";

</script>

<main>
    <h1 class="question display-5">{question}</h1>
    <div class="divSmileys">
        <a class="smiley" href="">
            <img  class="image1" src="sad.png" alt="Emoji rouge">
        </a>
        <a class="smiley" href="">
            <img  class="image2" src="moyen.png" alt="Emoji orange">
        </a>
        <a class="smiley" href="">
            <img  class="image3" src="sceptic.png" alt="Emoji jaune">
        </a>
        <a class="smiley" href="">
            <img  class="image4" src="happy-mid.png" alt="Emoji vert clair">
        </a>
        <a class="smiley" href="">
            <img  class="image5" src="happy.png" alt="Emoji vert">
        </a>
    </div>
    <a class="btn btn-primary retour " href="/main">Retour</a>

</main>

<style>

    .smiley{
        background-color: transparent;
        width: 12%;
        height: auto;
        border:0;
        margin:1%;
    }

    img{
        max-width: 100%;
        height: auto;
        width: auto;
    }

    .divSmileys{
        justify-content: center;
        display: flex;
        margin-top: 5%;
    }
    
    .retour{
        margin-top: 5%;
        margin-left: 5%;
    }

    .question{
        text-align: center;
        margin-top: 4%;
        margin-right: 20%;
        margin-left: 20%;
    }
</style>