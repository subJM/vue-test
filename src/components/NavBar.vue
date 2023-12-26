<template>
    <header>
        <article class="nav" >
          <div class="title" style="width:200px;"><a href="./index.html"><font-awesome-icon :icon="['fas', 'house']" />BANCO</a></div>
          <div id="menu" >
    
          </div>
          <div >
            <a href="./index.html">HOME</a>
          </div>
          <div>
            <router-link to="/about">About 페이지로 이동</router-link>
            <!-- <a href="./index.html">ABOUT</a> -->
          </div>
          <div>
            <a href="./index.html">NOTICE</a>
          </div>
          <div>
            <a href="./index.html">BUSINESS</a>
          </div>
          <div>
            <a href="./index.html">CONTACT</a>
          </div>
        
          <div style="width:200px;">
            <font-awesome-icon icon="fa-brands fa-square-twitter" style="width:50px;height:50px;" />
          </div>

        </article>
    </header>
</template>

<script></script>

<style>
div a {
  text-decoration: none;
  color:white;
}

li {
  list-style-type: none;
}

.nav {
  background-color: black;
  width: 100%;
  height: 80px;
}

.nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px 10px;
  color: white;
}

.title {
  font-size: 2em;
}

.title > a {
  color: white;
}
</style>