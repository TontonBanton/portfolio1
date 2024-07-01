<template>
  <div class="wrapper">
    <div class="main-container">
      <div class="container-one">
        <div class="profile">
          <img src="../assets/pic.jpg" alt="">
          <h2>Prestonn B. Ancla</h2>
          <h3>Junior Software Developer</h3>
        </div>
        <div class="social-links">
          <div class="link">
            <a href="">
              <img src="../assets/github.png" alt="">
              <h2>Github</h2>
            </a>
          </div>
          <div class="link">
            <a href="">
              <img src="../assets/linkedin.png" alt="">
              <h2>LinkedIn</h2>
            </a>
          </div>
          <div class="link">
            <a href="">
              <img src="../assets/twitter.png" alt="">
              <h2>Twitter</h2>
            </a>
          </div>
          <div class="link">
            <a href="">
              <img src="../assets/instagram.png" alt="">
              <h2>Instagram</h2>
            </a>
          </div>
        </div>
      </div>
      <div class="container-two">
        <div class="about-me">
          <h1>About Me</h1>
          <p> Enthusiastic Junior Front End Web Developer with a passion for
              building responsive and user-friendly web applications. Proficient in
              HTML, CSS, and JavaScript, with experience in popular framework like Vue.
              Adept at collaborating with designers and backend developers to create
              seamless and engaging user experiences. Committed to continuous learning
              and staying updated with the latest web development trends.
          </p>
        </div>
        <div class="technology-section">
          <h1>Technology Studied</h1>
          <div class="logos">
            <img src="../assets/js.png" alt="">
            <img src="../assets/node.png" alt="">
            <img src="../assets/vb.png" alt="">
            <img src="../assets/sql.png" alt="">
            <img src="../assets/css.png" alt="">
            <img src="../assets/html.png" alt="">
          </div>
        </div>
        <div class="button-container">
          <div class="projects-button"><a href="">My Projects</a></div>
          <div class="projects-button"><a href="">Curriculum Vitae </a></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style scoped>
  .wrapper{
    display: flex;
    justify-content: center;

  }
  img {
    height: 20px;
  }
  .main-container {
    width: 75%;
    display: flex;
    flex-direction: row;
    border-radius: 25px;
  }
  .container-one {
    padding: 2.5%;
    width: 30%;
    border-top-left-radius: 25px;
    border-bottom-left-radius: 25px;
    background-color: #7fc5fa;
  }
  .profile img {
    height: 5rem;
    border-radius: 50%;
  }
  .link a{
    text-decoration: none;
    color: #2c3e50;
    font-size: 10px;
  }
  .link img {
    height: 2rem;
  }

  .container-two {
    /* margin: 2.5%; */
    padding: 1.5%;
    width: 70%;
    border-top-right-radius: 25px;
    border-bottom-right-radius: 25px;
    background-color: rgb(106, 185, 238);
  }

  .about-me {
    text-align: left;
  }
  .logos img{
    margin: 5px;
    height: 2.5rem;
  }
  .button-container {
    margin-top: 5%;
    display: flex;
    flex-direction: row;
    justify-content: center;  /* align horizontally */
    align-items: center;      /* align vertically */
  }
  .projects-button {
    width: 20rem;
    border-radius: 15px;
    padding: 5px;
    margin: 5px;
    background-color: #0291ff;
  }
  .projects-button a{
    color: black;
    text-decoration: none;
  }
</style>
