<script>
import GitHubIcon from '@/components/icons/GitHubIcon.vue';
import CodePenIcon from '@/components/icons/CodePenIcon.vue';
import TwitterIcon from '@/components/icons/TwitterIcon.vue';
export default {
  components: {
    GitHubIcon,
    CodePenIcon,
    TwitterIcon
  }
}
</script>



<template>
  <div class="social-media-icon">
    <a href="#">
      <GitHubIcon />
    </a>
        <a href="#">
      <CodePenIcon />
    </a>
        <a href="#">
      <TwitterIcon />
    </a>
  </div>
</template>



<style lang="scss">
  .social-media-icon {
    svg {
      margin: 2rem 2rem 0 0;
      width: 3rem;
      path {
        fill: $ciGrey;
        transition: 250ms all ease-in-out;
      }
      &:hover, &:focus {
        path {
          fill: $ciBlue;
      }
      }
    }
  }
</style>