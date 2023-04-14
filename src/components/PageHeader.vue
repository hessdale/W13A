<template>
    <div>
<img class="rotate" width="100px" src="../assets/logo.png" alt="logo">
<nav>
    <a href="/public/index.html">Home</a>
    <a href="/public/index.html">Info</a>
    <a href="/public/index.html">Help</a>
</nav>
    </div>
</template>

<script>
    export default {
         
    }
</script>

<style scoped>

 @keyframes rotate_logo {
    from{transform: rotate(359deg)};
    to{transform:rotate(0deg)};
  }
  .rotate{
    animation: rotate_logo 3s cubic-bezier(0,0,0,0) infinite;
  }
div{
    display: grid;
    justify-items: center;
    grid-template-columns: 1fr 1fr;
    margin: 0;
    padding: 0;
    margin-bottom: 15px;
}
nav{
    display: grid;
    grid-template-rows: 1fr 1fr 1fr;
}
</style>