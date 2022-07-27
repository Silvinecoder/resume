
<main>
  <div class="main__container">
    <MainContainer />
  </div>
  <div class="side__container">
    <SideContainer />
  </div>
</main>

<script>
  import MainContainer from './lib/MainContainer.svelte';
  import SideContainer from './lib/SideContainer.svelte';

</script>

<style lang="scss">
  @import './lib/scss/main.scss';

  main {
    @media (min-width: $desktop--breakpoint) {
      display: flex;

      .main__container {
        width: 60%;
        order: 2;
      }

      .side__container {
        width: 40%;
      }
    }
  }
</style>
