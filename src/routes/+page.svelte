<script>
  import { displayName, description } from "$lib/copy"
</script>

<style>
  #container {
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-items: center;
    width: 100%;
    height: 100%;
  }

  #content {
    position: relative;
    top: 33%;
  }

  #description {
    color: var(--light-blue)
  }
</style>

<div id="container">
  <div id="content">
    <h1>{displayName}</h1>
    <h3 id="description">{description}</h3>
  </div>
</div>
