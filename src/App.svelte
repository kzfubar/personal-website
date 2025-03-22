<script>
  import profilePic from './assets/svelte.svg'; // Example profile picture
</script>

<main>
  <!-- Header Section -->
  <header>
    <img src={profilePic} alt="Profile Picture" class="profile-pic" />
    <h1>Your Name</h1>
    <p class="tagline">Web Developer | Designer | Lifelong Learner</p>
  </header>

  <!-- About Section -->
  <section class="about">
    <h2>About Me</h2>
    <p>
      Welcome to my personal website! I’m a passionate web developer with a love for creating
      beautiful, user-friendly applications. I specialize in front-end development and enjoy
      designing and building websites that make an impact.
    </p>
  </section>

  <!-- Links Section -->
  <section class="links">
    <h2>Find Me Online</h2>
    <ul>
      <li><a href="https://github.com/yourusername" target="_blank" rel="noreferrer">GitHub</a></li>
      <li><a href="https://linkedin.com/in/yourusername" target="_blank" rel="noreferrer">LinkedIn</a></li>
      <li><a href="https://twitter.com/yourusername" target="_blank" rel="noreferrer">Twitter</a></li>
    </ul>
  </section>
</main>

<style>
  :global(body) {
    margin: 0;
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f4f4f9;
  }

  main {
    padding: 2em;
    max-width: 800px;
    margin: 0 auto;
    text-align: center;
  }

  header {
    margin-bottom: 2em;
  }

  .profile-pic {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    border: 4px solid #646cffaa;
    margin-bottom: 1em;
  }

  h1 {
    margin: 0;
    font-size: 2.5em;
    color: #333;
  }

  .tagline {
    margin: 0.5em 0;
    font-size: 1.2em;
    color: #646cffaa;
  }

  section {
    margin-top: 2em;
    text-align: left;
  }

  section h2 {
    font-size: 1.8em;
    color: #646cff;
    border-bottom: 2px solid #646cffaa;
    padding-bottom: 0.3em;
  }

  .about p {
    font-size: 1.1em;
    margin: 0;
  }

  .links ul {
    list-style: none;
    padding: 0;
  }

  .links li {
    display: inline;
    margin-right: 1em;
  }

  .links a {
    text-decoration: none;
    color: #646cff;
    font-weight: bold;
    border-bottom: 1px solid transparent;
    transition: border-bottom 200ms;
  }

  .links a:hover {
    border-bottom: 1px solid #646cff;
  }
</style>