<template>
  <section class="home" id="home">
    <div class="container">
      <div class="row full-screen">
        <div class="home-content">
          <div class="block">
            <h6>Hello, My Name is</h6>
            <h1>Keshav Thakur</h1>
            <h6>Full Stack Developer</h6>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>

</script>

<style scoped>
.container {
  max-width: 1140px;
  margin: auto;
}

.row {
  display: flex;
  flex-wrap: wrap;
}
/* .home {
  min-height: 100vh;
  background-image: url("../assets/bg-cover.jpg");
  background-size: cover;
  position: absolute;
  left: 0;
  top: 0;
  width: 100%;
  background-position: center;
  padding: 15px;
} */

.home .full-screen {
  min-height: 100vh;
}

.home .home-content {
  flex: 0 0 100%;
  max-width: 100%;
  display: flex;
  flex-wrap: wrap;
  align-items: center;
}

.home .home-content .block {
  flex: 0 0 30%;
  max-width: 75%;
  /* padding-top: 50px; */
  padding-left: 35px;
  border-left: 5px solid black;
  margin-top: 50px;
}

.home .home-content .block h6 {
  color: black;
  background-color: mediumseagreen;
  font-size: 20px;
  margin: 0;
  padding: 0;
  float: left;
}

.home .home-content .block h1 {
    /* margin: 0; */
  color: black;
  background-color: pink;
  font-size: 50px;
  font-weight: 600;
  overflow: hidden;
  white-space: nowrap;
}

.home .home-content .block h6 {
  color: black;
  font-size: 20px;
  background-color: purple;
  margin: 0;
  padding: 0;
  float: left;
}
</style>
