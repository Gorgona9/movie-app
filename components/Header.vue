<template>
  <div>
    <div class="container-fluid">
      <v-container>
        <div class="content">
          <h1>Welcome</h1>
          <p>
            Millions of movies, TV shows and people to discover. Explore now.
          </p>
        </div>
      </v-container>
    </div>
  </div>
</template>
<script>
export default {

}
</script>
<style>
.container-fluid{
  /* i copy the image from unsplash website */
  background-image:url('../assets/background.jpg');
  width:100%;
  height: 50vh;
  background-position: center center;
  background-size: cover;
  background-repeat: no-repeat;
  display:flex;
  align-items: center;
  justify-content: center;
}
.content {
  text-align: end;
}
.content > h1,
.content > p {
  background-image: linear-gradient(#787878, #484848);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  -webkit-filter: drop-shadow(2px 2px #333);
  filter: drop-shadow(2px 2px #333);
}
</style>
