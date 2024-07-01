<template>
  <!--
     {{ projectData.ProjectsArray }}
  -->

  <div class="main-container">
    <div class="project-card" v-for="(items, index) in projectData.ProjectsArray" v-bind:key="items">     <!-- VFORLOOP-->
      <h2>{{ projectData.ProjectsArray[index].Title }}</h2>
      <img :src="projectData.ProjectsArray[index].Image" alt="">
      <p>{{ projectData.ProjectsArray[index].About }}</p>
      <div class="links">
        <a :href="projectData.ProjectsArray[index].Link1" target="blank"><img src="../assets/github.png" alt=""></a>
        <a :href="projectData.ProjectsArray[index].Link2" target="blank"><img src="../assets/link.png" alt=""></a>
      </div>
    </div>
  </div>

</template>

<script>
//import jsonData from"/projects.json"
import jsonData from "../../projects.json"

export default {
  data() {
    return { projectData: jsonData}
  }
}
</script>

<style scoped>
  .main-container {
    margin-top: 10px;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
  }
  .project-card {
    margin: 10px;
    padding: 10px;
    flex-wrap: 0 0 40%;
    background-color: white;
    border-radius: 25px;
    box-shadow: gray 0px 3px 8px;
  }
  .project-card img {
    height: 10rem;
  }
  .links {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-end;
  }
  .links img {
    height: 1.3rem;
    margin: 5px;
  }
</style>
