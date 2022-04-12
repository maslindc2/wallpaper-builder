<template>
 <!--Creates navigation bar-->
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/double">Double Wallpaper</router-link> |
    <router-link to="/stacked">Stacked Wallpaper</router-link> |
    <router-link to="/triple">Triple Wallpaper</router-link>
  </nav>
  <router-view/>
  <div class="double">
    <h1>This is a double page</h1>
    <p>Select two images to upload in order to build a dual monitor wallpaper</p>
    <div class="monitor1">
      <input type="file" id="image1" accept="image/png, image/jpeg">
    </div>
    <div class="monitor2">
      <input type="file" id="image2" accept="image/png, image/jpeg">
    </div>
    <input type="button" value="Build Wallpaper">
  </div>
</template>
<script>
export default {
}
</script>
<style>
</style>
