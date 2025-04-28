<script>
  //
</script>

<main class="homepage">
  <section class="content">
    <div class="text">
      <p class="intro">Hi there 👋 I'm</p>
      <h1>Kevin Fu</h1>
      <h2 class="subtitle">Software Developer | AI Enthusiast | Outdoors Enjoyer</h2>
      <p class="description">
        Welcome! I’m a developer passionate about building fun, user-friendly applications.
        Currently, I’m diving deep into AI and machine learning technologies, aiming to create tools that make a real impact.
        <br><br>
        If I’m not at my laptop, you might find me in the backcountry eating a Clif bar.
        <br>
        Have something you'd like to say? Feel free to reach out!</p>
      <p class="description"></p>
      <button class="hire-me">Contact Me</button>
    </div>

    <div class="image-wrapper">
      <img src="/pfp-2.png" alt="Profile" class="profile-pic" />
    </div>
  </section>
</main>

<style>

  /* Main Homepage Content */
  .homepage {
    min-height: 60vh;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 2em;
  }

  .content {
    display: flex;
    align-items: center;
    justify-content: space-between;
    max-width: 1200px;
    width: 100%;
    gap: 2em;
  }

  .text {
    flex: 1;
    text-align: left;
  }

  .intro {
    font-size: 1.2em;
    margin-bottom: 0.5em;
    color: #7d5a50;
  }

  h1 {
    font-size: 3em;
    margin: 0;
    color: #5c4033;
  }

  .subtitle {
    font-size: 1.5em;
    color: #a9745f;
    margin-top: 0.5em;
    margin-bottom: 1em;
  }

  .description {
    font-size: 1.1em;
    margin-bottom: 2em;
  }

  .hire-me {
    padding: 0.8em 2em;
    font-size: 1em;
    border: none;
    border-radius: 9999px;
    background-color: #a9745f;
    color: white;
    cursor: pointer;
    transition: background-color 0.3s;
  }

  .hire-me:hover {
    background-color: #7d5a50;
  }

  .image-wrapper {
    flex: .75;
    display: flex;
    justify-content: center;
  }

  .profile-pic {
    width: 400px;
    height: 400px;
    border-radius: 50%;
    border: 5px solid #a9745f;
    background-color: #fff4e6;
    object-fit: cover;
  }
</style>
