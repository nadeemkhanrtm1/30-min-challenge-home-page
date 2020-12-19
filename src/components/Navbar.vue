<template>
  <div class="navbar-container">
      <nav>
        <img alt="logo" src="../assets/logo.jpg"/>
        <div>
          <a>Home</a>
          <a>About</a>
          <a>Product</a>
          <a>Blog</a>
          <a>Contact  Us</a>
        </div>
      </nav>
  </div>
</template>

<script>
export default {
  name: 'Navbar',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.navbar-container{
  height: 80px;
  width:100vw;
  background: #e8e9e9;
}
nav{
  height: 100%;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: center;
  padding: 0 2%;
}
a{
  font-size: 1.5rem;
  margin-right:15px ;
}
</style>
