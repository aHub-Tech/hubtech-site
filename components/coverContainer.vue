<template>

   <div class="cover">
      <div class="cover_container">
         
         <div class="cover_text">
            <h2>A tecnologia conecta <span>pessoas</span> <br> e fortalece <span>comunidades</span> </h2>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Laboriosam quae voluptatum consectetur vel soluta labore unde rerum repellat perferendis, atque.</p>
            
            <div class="buttons">
               <button class="discord">Conheça a Hub</button>
               <button class="another_bt">
                  Outra Coisa
                  <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-arrow-right" width="44" height="44" viewBox="0 0 24 24" stroke-width="1.5" stroke="#2c3e50" fill="none" stroke-linecap="round" stroke-linejoin="round">
                     <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                     <line x1="5" y1="12" x2="19" y2="12" />
                     <line x1="13" y1="18" x2="19" y2="12" />
                     <line x1="13" y1="6" x2="19" y2="12" />
                  </svg>
               </button>
            </div>
         </div>
         
         
      </div>
   </div>

</template>

<style scoped>

   .cover {
      width: 100%;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
   }
   
   .cover .cover_container {
      width: 1300px;
      display: flex;
      justify-content: space-between;
      align-items: center;
   }
   
   .cover .cover_container .cover_text {
      width: 100%;
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      row-gap: 40px;
   }

   .cover .cover_container .cover_text h2 {
      color: white;
      font-size: 45px;
      letter-spacing: -2px;
      line-height: 50px;
   }
   
   .cover .cover_container .cover_text h2 span {
      color: var(--glow_yellow);
      font-style: italic;
      text-shadow: 0 0 2rem #eeff01;
   }
   
   .cover .cover_container .cover_text p {
      width: 600px;
      color: rgb(184, 184, 184);
      font-size: 18px;
      font-family: 'IBM Plex Sans', sans-serif;
      line-height: 30px;
   }

   .cover .cover_container .cover_text .buttons {
      display: flex;
      justify-content: flex-start;
      align-items: center;
      column-gap: 10px;
   }
   
   .cover .cover_container .cover_text .buttons .discord {
      font-family: 'IBM Plex Mono', sans-serif;
      font-size: 1rem;
      letter-spacing: 1px;
      background-color: #eeff01;
      border: none;
      padding: 1rem 1.5rem;
      border-radius: 0.375rem;
      text-transform: uppercase;
      cursor: pointer;
      font-weight: 600;
      box-shadow: 0 0 1rem #eeff01;
      transition: .3s;
   }
   
   .cover .cover_container .cover_text .buttons .discord:hover {
      box-shadow: 0 0 1rem #858f00;
      background-color: #cedd00;
   }
   
   
   .cover .cover_container .cover_text .buttons .another_bt {
      font-family: 'IBM Plex Mono', sans-serif;
      font-size: 1rem;
      letter-spacing: 1px;
      border: none;
      color: white;
      background: none;
      padding: 1rem 1.5rem;
      border-radius: 0.375rem;
      text-transform: uppercase;
      cursor: pointer;
      text-shadow: 0 0 2rem white;
      font-weight: 600;
      display: flex;
      justify-content: flex-start;
      align-items: center;
      transition: .3s;
   }
   .cover .cover_container .cover_text .buttons .another_bt:hover {
      text-shadow: none;
   }
   
   .cover .cover_container .cover_text .buttons .another_bt:hover svg {
      margin-left: 25px;
   }
   
   .cover .cover_container .cover_text .buttons .another_bt svg {
      margin-left: 15px;
      stroke: white;
      width: 20px;
      stroke-width: 2;
      filter: drop-shadow(0px 0px 4px rgb(255, 255, 255));
      transition: .3s;
   }

</style>