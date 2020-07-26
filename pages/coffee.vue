<template>
    <div class="flex flex-col relative  h-screen main">
      <div class="absolute watermak ">COFFEE</div>
      <div class="mx-8 pt-8 relative">
        <h1 class="text-white font-semibold text-5xl leading-10">ESPRESSO <br> 18.19</h1>
        <img class="relative" src="~/assets/images/coffee.png" alt="coffee package">
      </div>
      <div class="bg-white flex-grow rounded-t-lg rounded pt-12 px-8 card flex flex-col justify-between">
        <div class="flex justify-between">
          <h2 class="font-semibold text-2xl text-blue-700 leading-6">Pack Semaine. <br>1,- kg</h2>
          <div class="font-bold text-3xl text-orange-600">25,50 <small>€</small></div>
        </div>
        <div class="mt-2 text-xs">
          <p>Cette année notre mélange 100% Brésil a été
            confectionnédirectement à l’origine, au sein
            de la coopérative Cocarive.
          </p>
          <p class="mt-2">Après la sélection de parcelles de plantation,
            nous avons cuppé les lots de nos producteurs
            partenaires et assemblé des tasses aux profils
            compatibles. Nous avons retenu un assemblage
            de variétés catuai jaune et bourbon jaune,issues
            de terroirs singuliers et cultivés par deux producteurs
            distincts. Traités selon les méthodes de séchage
            post-récolte“honey” et “nature”,
            ces cafés s’accordent parfaitement.</p>
        </div>
        <div class="bg-orange-600 hover:bg-orange-700 text-white px-auto mb-4 font-bold py-2 px-8 text-center rounded-lg">Ajouter au panier</div>
      </div>
    </div>
</template>

<script>
    export default {
        name: "coffee"
    }
</script>

<style scoped>
  .main{
    overflow-x: hidden;
  }
  h1::before{
    display: block;
    content: " ";
    height: 5px;
    width: 150px;
    background-color: white;
    position: relative;
    top: -5px;
    left: 4px;
  }
  .watermak{
    color: #4B4B4B;
    mix-blend-mode: soft-light;
    font-weight: bold;
    font-size: 8rem;
    top: 50px;
    left: -50px;
  }
  .card{
    border-top-left-radius: 2rem;
    border-top-right-radius: 2rem;

  }

  img{
    top: 3rem;
    max-height: 300px;
  }
</style>
