<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
// import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div>
    <header class=" absolute top-0 w-full">
      
    </header>
    <main class="bg-black h-screen w-screen flex">
      <section id="section-1" class="main-section">
        <div class="absolute border-r-[1px] border-secondary bg-slate-800 h-screen w-1/4 z-10 text-center mt-">HELLO</div>
        <div class="main-section-cover pt-[19vh]">
          <h3>01</h3>
          <h1>Arts</h1>
          <p>"But I need to feel beautiful and holy things around me, always: music, mystery cults, symbols, myths. I need it, and I refuse to give it up... That's my fatal flaw." <br> - Hermann Hesse</p>
        </div>
      </section>
      <section id="section-2" class="main-section">
        <div class="main-section-cover pt-[30vh]">
          <h3>02</h3>
          <h1>Body</h1>
          <p>"What a disgrace it is for a man to grow old without ever seeing the beauty and strength of which his body is capable." <br> - Socrates</p>
        </div>
      </section>
      <section id="section-3" class="main-section">
        <div class="main-section-cover pt-[23vh]">
          <h3>03</h3>
          <h1>Polis</h1>
          <p>"In affairs between States, logic and sentiment do not weigh much compared to the realities of power: that which matters is what one can take and what one can hold on to." <br> - Charles de Gaulle</p>
        </div>
      </section>
      <section id="section-4" class="main-section border-none">
        <div class="main-section-cover border-none pt-[33vh]">
          <h3>04</h3>
          <h1>Mind</h1>
          <p>"We remain a mystery to ourselves, we fail to understand ourselves, we are bound to mistake ourselves. Of ourselves, we have no knowledge..." <br> - Nietzsche</p>
        </div>
      </section>
    </main>
    <footer>

    </footer>
  </div>
  <!-- <HelloWorld msg="Hello Vue 3 + Vite" /> -->
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@100;200;300;400;500;600;700;800;900&family=Playfair+Display:wght@400;500;600;700;800;900&family=Roboto:wght@100;300;400;500;700;900&display=swap');

h1, h3 {
  font-family: 'Playfair Display', serif;
}

* {
  font-family: 'Montserrat', sans-serif;
}
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
