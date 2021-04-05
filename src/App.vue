<template>
  <div id="app" class="relative ph5 pt5 h-100">
    <img src="./assets/bg-pattern-top-desktop.svg" alt="" class="absolute top-0 left-0">

    <section class="flex justify-around flex-column flex-row-ns">

      <section >

        <h1 class="f2 lh-title">10,000+ of our <br> users love our <br> products.</h1>
        <p class="lh-copy">We only provide great products combined with excellent <br> customer service.
          See what our satisfied customers <br> are saying about our services.
        </p>
      </section>
        <section class="flex flex-column mt5">
         <div class="w-75">
            <span><img src="./assets/icon-star.svg" alt=""></span> 
            <span><img src="./assets/icon-star.svg" alt=""></span> 
            <span><img src="./assets/icon-star.svg" alt=""></span> 
            <span><img src="./assets/icon-star.svg" alt=""></span> 
            <span><img src="./assets/icon-star.svg" alt=""></span> 
            <span>Rated 5 Stars in Reviews</span>
         </div>
         <div class="ml5 w-90">
            <span><img src="./assets/icon-star.svg" alt=""></span> 
            <span><img src="./assets/icon-star.svg" alt=""></span> 
            <span><img src="./assets/icon-star.svg" alt=""></span> 
            <span><img src="./assets/icon-star.svg" alt=""></span> 
            <span><img src="./assets/icon-star.svg" alt=""></span> 
            <span>Rated 5 Stars in Report Guru</span>
         </div>

         <div class="ml6 w-90">
            <span><img src="./assets/icon-star.svg" alt=""></span> 
            <span><img src="./assets/icon-star.svg" alt=""></span> 
            <span><img src="./assets/icon-star.svg" alt=""></span> 
            <span><img src="./assets/icon-star.svg" alt=""></span> 
            <span><img src="./assets/icon-star.svg" alt=""></span> 
            <span>Rated 5 Stars in BestTech</span>
         </div>
        </section>
      
    </section>
    <img src="./assets/bg-pattern-bottom-desktop.svg" alt="" class="absolute right-0 bottom-0">

  </div>
</template>

<script>

export default {
  name: 'App',
  
}
</script>

<style>
  html,body {
    height: 100%;
    /* overflow: hidden; */
  }
 
  section section:first-of-type h1 {
    color: hsl(300, 43%, 22%);
  }

  section section:first-of-type p {
    color: hsl(303, 10%, 53%);
  }

  section section:nth-of-type(2) div {
    background:hsl(300, 24%, 96%);
    padding: 1rem 2.5rem 1rem 1.5rem ;
   margin-bottom: 1.5rem;
    font-weight: 700;
    color:hsl(300, 43%, 22%);
    border-radius: 8px;
  }

  section section:nth-of-type(2) div span:last-child{
    padding: 0 0 0 1.5rem;
  }

  body {
    font-family: 'Spartan', sans-serif;
    font-size: 15px;
  }
</style>

