<script lang="ts">

    let question = "Quelle est votre satisfaction globale au regard de l’accueil qui vous a été réservé ?";

</script>

<main>
    <h1 class="question display-5">{question}</h1>
    <div class="divSmileys">
        <button class="smiley">
            <img  class="image1" src="sad.png" alt="Emoji rouge">
        </button>
        <button class="smiley">
            <img  class="image2" src="moyen.png" alt="Emoji orange">
        </button>
        <button class="smiley">
            <img  class="image3" src="sceptic.png" alt="Emoji jaune">
        </button>
        <button class="smiley">
            <img  class="image4" src="happy-mid.png" alt="Emoji vert clair">
        </button>
        <button class="smiley" href="/main">
            <img  class="image5" src="happy.png" alt="Emoji vert">
        </button>
    </div>
    <a class="btn btn-primary retour" href="/main">Retour</a>

</main>

<style>

    .smiley{
        background-color: transparent;
        width: 12%;
        height: auto;
        border:0;
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