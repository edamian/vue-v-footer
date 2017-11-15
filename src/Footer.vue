<template>
    <div class="columns is-mobile is-desktop" id="footer">
        <div class="column has-text-centered is 3">
            <a class="button" href="#">
                <img :src="fb">
            </a>
        </div>
        <div class="column is-3 has-text-centered">
            <a class="button" href="#">
                <img :src="tw">
            </a>
        </div>
        <div class="column is-3 has-text-centered">
            <a class="button" href="#">
                <img :src="gm">
            </a>
        </div>
        <div class="column is-3 has-text-centered">
            <a class="button" href="#">
                <img :src="linkedin">
            </a>
        </div>
    </div>
</template>

<script>
export default {
  name: 'footer',
  data() {
      return {
          fb: './src/assets/img/facebook.png',
          tw: './src/assets/img/twitter.png',
          yt: './src/assets/img/youtube.png',
          gm: './src/assets/img/google-plus.png',
          linkedin: './src/assets/img/linkedin.png'
      }
  }
}
</script>

<style>
#footer {
    background-color: #996244;
    margin-top: 10px;
}
</style>
