<template>
  <div id="app">
    <div id="nav">
      <div id="logo">
        <router-link to="/">
         <img id="logo" src="./assets/ehrenapp-logo.png" alt="Logo">
        </router-link>
        
      </div>
      <div  class="nav-icon" @click="openNav()" v-bind:class="{nav_icon_opened: this.showNav}">
        <svg xmlns="http://www.w3.org/2000/svg" width="30" height="80" viewBox="0 0 191 152">
          <g id="Group_43" data-name="Group 43" transform="translate(-1948 -4244)">
            <rect id="Rectangle_56" data-name="Rectangle 56" width="191" height="29" rx="14.5" transform="translate(1948 4244)" fill="#fff"/>
            <rect id="Rectangle_57" data-name="Rectangle 57" width="148" height="29" rx="14.5" transform="translate(1991 4306)" fill="#fff"/>
            <rect id="Rectangle_58" data-name="Rectangle 58" width="96" height="29" rx="14.5" transform="translate(2043 4367)" fill="#fff"/>
          </g>
      </svg>
      </div>
      <div class="nav-close-icon" @click="closeNav()" v-bind:class="{nav_icon_close_opened: this.showNav}">
        <svg xmlns="http://www.w3.org/2000/svg" width="30" height="80" viewBox="0 0 173.282 173.282">
  <g id="Group_43" data-name="Group 43" transform="translate(-1956.718 -4482)">
    <rect id="Rectangle_59" data-name="Rectangle 59" width="212.754" height="32.303" rx="16.151" transform="translate(1979.56 4482) rotate(45)" fill="#fff"/>
    <rect id="Rectangle_60" data-name="Rectangle 60" width="212.754" height="32.303" rx="16.152" transform="translate(2130 4504.841) rotate(135)" fill="#fff"/>
  </g>
</svg>

      </div>
      <div class="links" @click="closeNav()" v-bind:class="{nav_open: this.showNav}">
        <router-link to="/" class="link">Home</router-link>
        <!--<router-link to="/about" class="link">Über uns</router-link>-->
        <router-link to="/privacy" class="link">Datenschutz</router-link>
        <div id="signup-button" class="link">
          <router-link to="/">Runterladen</router-link>
        </div>
      </div>
    </div>
    <router-view id="router-view"/>
    
  </div>
</template>
<script>

export default {
  name: "App",
  methods: {
    openNav(){
      this.showNav = true;
      console.log("Nav open");
    },
    closeNav(){
      this.showNav = false;
      console.log("Nav closed");
    },
  },
  data ()  {
    return {
      showNav: false,
    };
  }
};
</script>
<style>
* {
  margin: 0;
  padding: 0;
}

@font-face {
  font-family: "Gilroy";
  src: url("./assets/fonts/Gilroy-Light.otf");
  font-style: normal;
  font-weight: 300;
}

@font-face {
  font-family: "Gilroy";
  src: url("./assets/fonts/Gilroy-ExtraBold.otf");
  font-style: normal;
  font-weight: 800;
}

body{
  background-color: #21262D;
}
#app {
  font-family: Gilroy, Helvetiva, sans-serif;
  text-align: center;
  margin: 0;
  color: #fff;
}
#router-view {
  position: absolute;
  width: 100%;
  height: 100%;
}

#nav {
  padding: 0 15%;
  margin-top: 3%;
  position: absolute;
  width: 100%;
  top: 0;
  z-index: 1000;
  display: flex;
  justify-content: space-between;
  align-items: center;
  box-sizing: border-box;
}

#logo{
  width: 150px;
}

.nav-icon{
  display: none;
}

.nav-close-icon{
  display: none;
}

.links {
  display: flex;
}


#nav a {
  text-decoration: none;
  color: #fff;
  font-size: 16px;
  font-weight: 800;
  margin: 0 30px;
}

#nav a.router-link-exact-active {
  color:#FFE958;
}

#signup-button a {
  background-color: #FFE958;
  padding: 15px 35px;
  color: #21262D;
  border-radius: 100px;
  transition: 0.2s ease-in;
  word-wrap: none;
  overflow-wrap: initial;
}
#signup-button a:hover {
  transform: scale(1.03);
  box-shadow: 0 0px 15px rgba(255, 233, 88, 0.3);
  transition: 0.2s ease-out;
}
#signup-button a.router-link-exact-active {
  color: #21262D;
}
@media screen and (max-width: 1280px) {
  #nav {
    padding: 0 5%;
  }
  
}

@media screen and (max-width: 970px) {
  #nav{
    align-items: center;
    height: 80px;
    margin: 0;
    padding: 0 20px;
  }
  .nav-icon{
    display: block;
    position: absolute;
    z-index: 100;
    top:0;
    right: 20px;
  }

  .nav_icon_opened{
    display: none;
  }


  .nav-close-icon{
    position: fixed;
    z-index: 100;
    top:0;
    right: 20px;
  }

  .nav_icon_close_opened{
    display: block;
  }


  .links{
    width: 50%;
    height: 100vh;
    position: fixed;
    top: 0;
    right: 0;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    background-color: #21262D;
    display: none;
    transition: 0.2s ease-out;
    -webkit-box-shadow: 0px 0px 40px -2px rgb(19, 21, 22);
-moz-box-shadow: 0px 0px 40px -2px rgb(19, 21, 22);
box-shadow: 0px 0px 40px -2px rgb(19, 21, 22);
  }
  #first-link{
    margin-top: 80px;
  }

  .nav_open{
    display: flex;
    transition: 0.2s ease-out;
  }

  #nav a{
    margin: 40px 0px 40px 0 ;
    color: white,
  }

  

#signup-button{
  margin: 40px 0;
}
  
}


</style>
