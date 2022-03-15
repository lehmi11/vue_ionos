<script>
import SocialNetworks from '@/components/SocialNetworks.vue'
export default {
  components: {
    SocialNetworks
  }
}
</script>


<template>
  <article class="intro-text">
    <p class="intro-hello">Hi, my name is Patrick</p>
    <h1>I am a Front-End Developer <br>and UI/UX Designer</h1>
    <p class="content">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quo, sed omnis porro quasi illo tempore nobis optio! Quod eaque cumque illum maiores, repellat veniam non iusto. Voluptas magni quod dolores.</p>
    <SocialNetworks />
  </article>


</template>



<style lang="scss" scoped>
  .intro-text {
    color: $ciWhite;
    max-width: 40rem;
    font-family: $roboto;

    p {
      font-size: 1.5rem;
      padding: 0;
      margin: 0;
      &.intro-hello {
        margin: 2rem 0 1rem 0;
      }
      &.content {
        margin: 0 0 2rem 0;
        line-height: 1.4rem;;
        color: $ciGrey;
      }
    }
    h1 {
      font-size: 2.5rem;
      padding: 0;
      margin: 0 0 1rem 0;
    }
  }
</style>