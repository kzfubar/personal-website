<!-- src/routes/+layout.svelte -->

<script>
  //
</script>

<nav class="navbar">
  <div class="nav-content">
    <ul class="nav-links">
      <li><a href="/">Home</a></li>
      <li><a href="/under_development">About</a></li>
      <li><a href="/under_development">Projects</a></li>
    </ul>
    <ul class="nav-links">
      <li><a href="/under_development" > <img src="/github_icon.svg"title="Github" alt="Github" class="icon"/></a></li>
      <li><a href="/under_development" > <img src="/linkedin_icon.svg" title="LinkedIn" alt="LinkedIn" class="icon"/></a></li>
      <li><a href="/under_development" > <img src="/resume_icon.svg" title="Download Resume" alt="Resume" class="icon"/></a></li>
    </ul>
  </div>
</nav>

<slot />

<footer class="footer">
  © 2025 Kevin Fu
</footer>

<style>
  :global(body) {
    margin: 0;
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    color: #3b2f2f;
    background-color: #faf3e0;
  }
      /* Top Navigation Bar */

  .navbar {
    width: 100%;
    background-color: #fff4e6;
    padding: 1em 2em;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    position: sticky;
    top: 0;
    z-index: 100;
  }

  .nav-content {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1200px;
    margin: 0 auto;
  }

  .nav-links {
    list-style: none;
    display: flex;
    gap: 2em;
    margin: 0;
    padding: 0;
  }

  .nav-links li a {
    text-decoration: none;
    color: #5c4033;
    font-weight: bold;
    transition: color 0.3s;
  }

  .nav-links li a:hover {
    color: #a9745f;
  }

    .icon {
        width: 25px;
        height: 25px;
        object-fit: cover;
    }

    .footer {
        align-items: center;
        min-height: 30vh;
        display: flex;
        justify-content: center;
    }

</style>
