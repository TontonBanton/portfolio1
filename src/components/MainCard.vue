<template>
  <div class="main-container">

    <div class="container-one">
      <div class="profile">
        <img src="../assets/pic.jpg" alt="">
        <h3>Name Here</h3>
        <p>Software Developer</p>
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
      <p>Lorem, ipsum dolor sit amet consectetur adipisicing
        elit.Esse quidem iure magni incidunt quas. Doloremque
        itaque delectusquae quaerat fugiat, id dolorum mollitia
        sapiente, dicta cumque cupiditate et eveniet labore?
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
      <div class="projects-button">
        <a href="">My Projects</a>
      </div>
      <div class="projects-button">
        <a href="">Curriculum Vitae </a>
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
  img {
    height: 20px;
  }
  .main-container {
    display: flex;
    flex-direction: row;
    background-color: gray;
    border-radius: 25px;
  }

  .container-one {
    background-color: lightcoral;
    padding: 2.5%;
    width: 30%;
    border-radius: 25px;
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
    background-color: skyblue;
    margin: 2.5%;
    width: 70%;
    /*border-radius: 25px;*/
  }
  .about-me {
    text-align: left;
  }
  .logos img{
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
    background-color:green;
    border-radius: 15px;
    padding: 5px;
    margin: 5px;
  }
  .projects-button a{
    color: white;
    text-decoration: none;
  }
</style>
