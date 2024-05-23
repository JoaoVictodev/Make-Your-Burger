<template>
  <id id="main-banner">
    <h1>Make Your Burguer</h1>
  </id>
</template>

<script>
export default {
  name: "Banner",
  burgue: "",
};
</script>

<style scoped>
#main-banner {
  background: url("../../public/img/burger.jpg");
  background-position: 0 -250px;
  background-size: cover;
  display: flex;
  align-items: center;
  justify-content: flex-start;
  height: 500px;
}

#main-banner h1 {
  color: #fff;
  text-align: center;
  font-size: 60px;
  background: #222;
  padding: 30px;
}
</style>
