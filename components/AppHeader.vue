<template>
  <header class="header">
    <div> <h1 class="title">Drink App</h1></div>
  <ul>
    <li>
        <nuxt-link to="/">Home</nuxt-link>
    </li>
    <li>
        <nuxt-link to="/drinks">Drinks</nuxt-link>
    </li>
    <li>
        <nuxt-link to="/about">About</nuxt-link>
    </li>
  </ul>
</header>
</template>

<script>
export default {
    name: 'AppHeader'
}
</script>

<style>
.header{
    display: flex;
    flex-wrap: wrap;  
    justify-content: space-between;
    align-items: center;
    margin-bottom: 1rem; 
    padding-bottom: 1rem; 
    border-bottom: 1px dotted #ccc;
}
.header .title {
    font-size: 3rem; 
    color: #526488;
}
.header ul{
    display: flex; 
}
.header a {
    display: inline-block; 
    background: #333; 
    color: #fff; 
    padding: 0.3rem 1rem; 
    margin-right: 0.5rem; 
    border-radius: 3px; 
}
</style>