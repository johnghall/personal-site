<script>
  import '../app.css'
</script>

<style>
  #main {
    height: 100%;
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-tems: center;
    padding: 20px;
  }

  #navBar {
    height: 50px;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: center;
    color: white;
    gap: 40px;
    margin-left: 20px;
  }

  a {
    text-decoration: underline;
    color: inherit;
  }
</style>

<div id="main">
  <nav id="navBar">
    <a href="/"><h3>Home</h3></a>
    <a href="/blog"><h3>Dev Blog</h3></a>
    <a href="/projects"><h3>Projects</h3></a>
    <a href="/about"><h3>About</h3></a>
  </nav> 
  <slot />
</div>

