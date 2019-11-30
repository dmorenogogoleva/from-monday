<script>
  let title = "спонедельника";
</script>

<style>
  .title {
    text-transform: lowercase;
    position: fixed;
    left: 50%;
    top: 5vw;
    transform: translateX(-50%);
    color: whitesmoke;
    font-size: 12.5vw;
  }

  @media (max-width: 414px) {
    .title {
      top: 40vw;
    }
  }
</style>

<h1 class='title'>{title}</h1>
