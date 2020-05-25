<template>
  <div class="about_game app-page p-3  d-flex justify-content-center">
    <div class="inner" style="max-width:600px;">
      <h1 class="text-center">About game</h1>
      <p>A Tic-Tac-Toe game I built as an exam for my last work. 
        <br>
        they wanted a simple game, I've created an online game to play with my kids.
      </p>
      <section class="my-3">
        <h3 class="mb-3">Tech Stack</h3>
        <h5 class="mb-3">Front:</h5>
        <ul>
          <li>Vue</li>
          <li>Vuetify</li>
          <li>Bootstrap</li>
          <li>Socket IO</li>
          <li>Axios</li>
          <li>deploy to Surge.sh</li>
        </ul>

        <h5 class="my-3">Back:</h5>
        <ul>
          <li>Koa</li>
          <li>Mongo</li>
          <li>Mongoos</li>
          <li>DB host at mlab.com</li>
          <li>Socket IO</li>
          <li>deploy to Heroku</li>
        </ul>
      </section>



      <section class="mb-3">
        <h3 class=" mb-1">How To Play?</h3>

        <p>
          open the page in 2 windows from 2 deferent browsers (or 1 incognito).
          <br>
          create 2 users (you can login as user1 and user2 - password 123456).
          <br>

          games page will show all active and eneded games.
          <br>
          you can ask to join a game. a notification will appear at the game opener window.
        
          
        </p>
      </section>
    </div>
  </div>
</template>
<script>
export default {
  name: "About"
};
</script>
<style lang="scss" scoped>
.about {
  .img {
    max-width: 30rem;
    img {
      max-width: 100%;
    }
  }
}
</style>
