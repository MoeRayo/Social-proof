<template>
  <div id="app">

    <div id="wrapper"  class="relative ph6-ns ph4-m ph3 pt5">

      <img src="./assets/bg-pattern-top-desktop.svg" alt="" class="absolute top-0 left-0">
      <img src="./assets/bg-pattern-bottom-desktop.svg" alt="" class="absolute right-0 bottom-0">
      
      <section class="flex flex-column flex-row-l justify-around">

        <section class="products-header tc tl-l w-30-l w-50-m self-center-m">

          <h1 class="f3 f2-l lh-title ">10,000+ of our <br>      users love our <br> products.</h1>
          <p class="lh-copy f6 w-0">We only provide great        products combined with excellent customer service. See what our satisfied customersare saying about our services.
          </p>

        </section>

        <section class="reviews flex flex-column mt5-l mt4 mb3-m tc">

          <div>
              <span><img src="./assets/icon-star.svg" alt=""></span> 
              <span><img src="./assets/icon-star.svg" alt=""></span> 
              <span><img src="./assets/icon-star.svg" alt=""></span> 
              <span><img src="./assets/icon-star.svg" alt=""></span> 
              <span><img src="./assets/icon-star.svg" alt=""></span> 
              <p class="di-ns ml4">Rated 5 Stars in Reviews</p>
          </div>

          <div>
              <span><img src="./assets/icon-star.svg" alt=""></span> 
              <span><img src="./assets/icon-star.svg" alt=""></span> 
              <span><img src="./assets/icon-star.svg" alt=""></span> 
              <span><img src="./assets/icon-star.svg" alt=""></span> 
              <span><img src="./assets/icon-star.svg" alt=""></span> 
              <p class="di-ns ml4">Rated 5 Stars in Report Guru</p>
          </div>

          <div>
            <span><img src="./assets/icon-star.svg" alt=""></span> 
            <span><img src="./assets/icon-star.svg" alt=""></span> 
            <span><img src="./assets/icon-star.svg" alt=""></span> 
            <span><img src="./assets/icon-star.svg" alt=""></span> 
            <span><img src="./assets/icon-star.svg" alt=""></span> 
            <p class="di-ns ml4">Rated 5 Stars in BestTech</p>
          </div>

        </section>
      </section>

      <section class="cards flex flex-row-l justify-between flex-column"> 

        <section>

          <div class="card-avatar flex">
            <img src="./assets/image-colton.jpg" alt=""> 

            <div class="cards-info ml3">
              <p>Colton Smith</p>
              <small>Verified Buyer</small>
            </div>
          </div>

          <p class="lh-title">"We needed the same printed design as the one we had ordered a week prior. Not only did they find the original order, but we also received it in time. Excellent!"</p>
        </section>

        <section>

          <div class="card-avatar flex">
            <img src="./assets/image-irene.jpg" alt=""> 

            <div class="cards-info ml3">
              <p>Colton Smith</p>
              <small>Verified Buyer</small>
            </div>
          </div>
            
          <p class="lh-title">"Customer service is always excellent and very quick turn around. Completely delighted with the simplicity of the purchase and the speed of delivery."</p>
        </section>

        <section>
          <div  class="card-avatar flex">
            <img src="./assets/image-anne.jpg" alt=""> 

            <div class="cards-info ml3">
              <p>Colton Smith</p>
              <small>Verified Buyer</small>
            </div>
          </div>

          <p class="lh-title">"Put an order with this company and can only praise them for the very high standard. Will definitely use them again and recommend them to everyone!"</p>
        </section>

      </section>

    </div>
     
  </div>
</template>

<script>

export default {
  name: 'App',
  
}
</script>

<style>
  html,body {
    /* height: 100%; */
    /* overflow: hidden; */
  }
 
  section section:first-of-type h1 {
    color: hsl(300, 43%, 22%);
  }

 .products-header p {
    color: hsl(303, 10%, 53%);
  }

  .reviews div {
    background:hsl(300, 24%, 96%);
    padding: 1rem 2.5rem 1rem 1.5rem ;
   margin-bottom: 1.5rem;
    font-weight: 700;
    color:hsl(300, 43%, 22%);
    border-radius: 8px;
    width: 90%;
  }

.reviews div:nth-of-type(2) {
  margin-left: 3rem;
}

.reviews div:nth-of-type(3) {
  margin-left: 6rem;
}
  section section:nth-of-type(2) div span:last-child{
    padding: 0 0 0 1.5rem;
  }

  .cards {
    margin: 0 auto;
    /* width: 85%; */
    /* background: red; */
  }

  .cards section {
    background:hsl(300, 43%, 22%);
    border-radius: 8px;
    margin: 4rem 1rem;
    padding: 2rem;
    color: hsl(0, 0%, 100%);
  }

.cards article {
  margin: 2rem;
}
  .cards section img {
    border-radius: 50%;
  }

.cards section:nth-of-type(2){
  /* margin-top: 5rem; */
}
  .cards section p{
    /* width: 80%; */
  }

  .cards-info {
    display: inline-block;
    /* padding-left: 2rem; */
  }
/* .cards-info section {
  height: 100px;
} */
  .cards-info p {
    font-weight: 500;
  }
  small {
    display: block;
    margin-top: -0.5rem;
    color: hsl(333, 80%, 67%);
  }
  .card-avatar {

  }

  body {
    font-family: 'Spartan', sans-serif;
    font-size: 15px;
  }

/* @media screen and (max-width:1334px) and (min-width:751px){ 
  .cards{
    width: 100%;
    font-size: 0.8rem;
  }

  .reviews div {
    width: 100%;

    margin: 0 auto 1.5rem auto;
  }
  .reviews div:nth-of-type(2), .reviews div:nth-of-type(3) {
  /* margin-left:auto; */
  /* margin:  0 auto; */

@media screen and (max-width:959px) and (min-width:657px){ 
  .products-header {
    /* width: 50%; */
  }
  .cards {
    width: 50%;
    margin: 0 auto;
    flex-direction: column;
  }
  .cards section{
    width: 100%;
    margin-top: 1rem;
  }
}
@media only screen and (max-width:750px) {
  /* .products-header {
    text-align: center;
  } */
 span {
   margin: 0.15rem;
 }

 .reviews div {
   width: 100%;
    margin: 0 auto 1.5rem auto;

 }
.reviews div:nth-of-type(2), .reviews div:nth-of-type(3) {
  margin-left:auto;
}
 .cards {
   width: 100%;
 }

.cards section {
   
    margin: 1rem 0rem;
}
}

</style>

