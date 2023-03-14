<template>
  <div class="home">
    <img alt="Solver logo" src="../assets/logo.svg" />
    <h1>Solver Media Brand Manual title</h1>
    <p>
      Some text about the point of this manual, what you can find in here, how
      you can use it and what you can do here. Maybe also give some links to the
      most requested things right away (like logo files, etc)
    </p>
    <video id="background-video" autoplay loop muted>
      <source src="../assets/158e8a26-5b063943.mp4" type="video/mp4" />
    </video>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "HomeView",
  components: {},
};
</script>

<style>
.home {
  width: 100%;
  height: 500px;
}

h1 {
  color: white;
}

.home p {
  padding: 30px;
  background: white;
  width: 800px;
  margin-left: auto;
  margin-right: auto;
}

.home img {
  width: 80px;
  height: 80px;
  margin-left: auto;
  margin-right: auto;
  margin-top: 20px;
  background: white;
  padding: 10px;
  border-radius: 50%;
}

#background-video {
  width: 100vw;
  height: 500px;
  object-fit: cover;
  position: fixed;
  left: 0;
  right: 0;
  top: 0;
  bottom: 0;
  z-index: -1;
}
</style>
