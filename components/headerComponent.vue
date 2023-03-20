<template>

   <header>
      <div class="header_container">
         <h2><span>HUB</span>Tech</h2>
         
         <div class="header_links">
            <a href="#">Inicio</a>
            <a href="#">Discord</a>
            <a href="#">Sobre</a>
         </div>
      </div>
   </header>

</template>

<script setup>

   

</script>


<style scoped>

   header {
      width: 100%;
      display: flex;
      justify-content: center;
      align-content: center;
      border-bottom: 1px solid #131313;
      padding: 20px 0px;
      position: absolute;
      top: 0;
      left: 0;
   }
   
   header .header_container {
      width: 1300px;
      display: flex;
      justify-content: space-between;
      align-items: center;
   }
   
   header .header_container h2 {
      font-size: 25px;
      color: var(--white);
      font-weight: 900;
      text-shadow: 0 0 1rem #ffffff;
   }
   
   header .header_container h2 span {
      font-weight: 400;
      color: var(--glow_yellow);
      text-shadow: 0 0 1rem #eeff01;
   }
   
   header .header_container .header_links {
      display: flex;
      justify-content: space-between;
      align-items: center;
      column-gap: 50px;
   }
   
   header .header_container .header_links a {
      font-weight: 500;
      color: rgb(105, 105, 105);
      font-size: 14px;
      text-decoration: none;
      transition: .3s;
      cursor: pointer;
   }

   header .header_container .header_links a:hover {
      color: white;
   }

</style>