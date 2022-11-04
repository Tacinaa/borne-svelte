<script lang="ts">

    let question = "Quelle est votre satisfaction globale au regard de l’accueil qui vous a été réservé ?";

</script>

<main>
    <h1 style="text-align: center">{question}</h1>
    <div class="divSmileys">
        <button class="smiley">
            <img  class="image5" src="happy.png" alt="Emoji vert">
        </button>
        <button class="smiley">
            <img  class="image4" src="happy.png" alt="Emoji vert clair">
        </button>
        <button class="smiley">
            <img  class="image3" src="happy.png" alt="Emoji jaune">
        </button>
        <button class="smiley">
            <img  class="image2" src="happy.png" alt="Emoji orange">
        </button>
        <button class="smiley">
            <img  class="image1" src="happy.png" alt="Emoji rouge">
        </button>
    </div>

</main>

<style>

    .smiley{
        background-color: transparent;
        width: 15%;
        height: auto;
        border:0;
    }

    img{
        max-width: 100%;
        height: auto;
        width: auto\9;
    }



    .divSmileys{
        justify-content: center;
        display: flex;
        padding-top: 10%;
    }

</style>