<template>
  <div id="app">
    <div id="nav">
      <div id="logo">
        <router-link to="/">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="150"
            height="33.912"
            viewBox="0 0 177.5 33.912"
          >
            <g id="logo-svg" transform="translate(-278 -73)">
              <g id="Gruppe_7" data-name="Gruppe 7" transform="translate(-28)">
                <path
                  id="Pfad_7"
                  data-name="Pfad 7"
                  d="M13.356-17.82a5.267,5.267,0,0,0-1.584-.216,6.179,6.179,0,0,0-4.9,2.34V-17.82H2.412V0h4.86V-8.892c0-3.06,1.872-4.644,4.788-4.644h1.3ZM32.4-7.272a11.464,11.464,0,0,0,.324-2.664,8.108,8.108,0,0,0-8.388-8.28,9.191,9.191,0,0,0-9.324,9.324A9.341,9.341,0,0,0,24.768.432,10.9,10.9,0,0,0,31.9-2.232L29.88-5.544a8.035,8.035,0,0,1-4.968,1.8c-2.592,0-4.428-1.26-5-3.528Zm-12.492-3.42a4.389,4.389,0,0,1,4.248-3.6,3.626,3.626,0,0,1,3.852,3.6Zm31.536.108c0-4.932-2.988-7.632-7.632-7.632a9.717,9.717,0,0,0-7.776,3.672l2.52,2.988C40.14-13.248,41.436-14,43.272-14c2.16,0,3.312,1.152,3.312,3.132v.792H42.12c-4.14,0-6.732,1.98-6.732,5.184,0,3.132,2.376,5.328,6.156,5.328a7.424,7.424,0,0,0,5.436-2.16V0h4.464ZM46.584-6.66A3.543,3.543,0,0,1,42.84-3.132c-1.548,0-2.556-.756-2.556-1.944s.9-1.8,2.484-1.8h3.816ZM69.084-27v10.908a6.887,6.887,0,0,0-5.328-2.124c-4.968,0-8.64,3.96-8.64,9.324S58.788.432,63.756.432A6.78,6.78,0,0,0,69.48-2.2V0h4.464V-27Zm.072,18.108c0,3.2-2.052,4.9-4.5,4.9-2.628,0-4.608-1.944-4.608-4.932a4.6,4.6,0,0,1,4.608-4.9C67.1-13.824,69.156-12.06,69.156-8.892Zm25.992,1.62a11.463,11.463,0,0,0,.324-2.664,8.108,8.108,0,0,0-8.388-8.28A9.191,9.191,0,0,0,77.76-8.892,9.341,9.341,0,0,0,87.516.432a10.9,10.9,0,0,0,7.128-2.664L92.628-5.544a8.035,8.035,0,0,1-4.968,1.8c-2.592,0-4.428-1.26-5-3.528Zm-12.492-3.42a4.389,4.389,0,0,1,4.248-3.6,3.626,3.626,0,0,1,3.852,3.6ZM110.2-17.82a5.267,5.267,0,0,0-1.584-.216,6.179,6.179,0,0,0-4.9,2.34V-17.82H99.252V0h4.86V-8.892c0-3.06,1.872-4.644,4.788-4.644h1.3Zm15.192,0-4.644,11.7-4.356-11.7H111.24l6.84,16.74L117.54.144a3.547,3.547,0,0,1-3.708,2.412c-.288,0-.972-.036-2.088-.144V6.48a12.14,12.14,0,0,0,3.132.432c3.312,0,5.472-1.656,7.092-5.364L130.5-17.82Z"
                  transform="translate(353 100)"
                  fill="#282B37"
                />
                <g
                  id="Icon_ionic-ios-book"
                  data-name="Icon ionic-ios-book"
                  transform="translate(302.618 73.5)"
                >
                  <path
                    id="Pfad_1"
                    data-name="Pfad 1"
                    d="M11.895,4.507c4.7,0,8.7,1.962,8.7,5.766V11.4h0V31.359c0,.155-.27.19-.33.049V31.4A7.846,7.846,0,0,0,13.1,26.445a12.548,12.548,0,0,0-8.1,2.609,1.054,1.054,0,0,1-.574.2H4.043c-.322,0-.661-.19-.661-.429V8.452C3.373,6.195,7.191,4.507,11.895,4.507Z"
                    fill="#46ccff"
                  />
                  <path
                    id="Pfad_2"
                    data-name="Pfad 2"
                    d="M27.4,4.5c-4.7,0-8.7,1.962-8.7,5.766v1.125h0V31.352c0,.155.27.19.33.049v-.007a7.935,7.935,0,0,1,7.156-4.957,12.546,12.546,0,0,1,8.1,2.609,1.113,1.113,0,0,0,.574.2h.391c.322,0,.661-.19.661-.429V8.438C35.92,6.188,32.1,4.5,27.4,4.5Z"
                    transform="translate(3.626)"
                    fill="#46ccff"
                  />
                </g>
              </g>
            </g>
          </svg>
        </router-link>
        
      </div>
      <div  class="nav-icon" @click="openNav()" v-bind:class="{nav_icon_opened: this.showNav}">
        <svg xmlns="http://www.w3.org/2000/svg" width="30" height="80" viewBox="0 0 191 152">
          <g id="Group_43" data-name="Group 43" transform="translate(-1948 -4244)">
            <rect id="Rectangle_56" data-name="Rectangle 56" width="191" height="29" rx="14.5" transform="translate(1948 4244)" fill="#1B1F23"/>
            <rect id="Rectangle_57" data-name="Rectangle 57" width="148" height="29" rx="14.5" transform="translate(1991 4306)" fill="#1B1F23"/>
            <rect id="Rectangle_58" data-name="Rectangle 58" width="96" height="29" rx="14.5" transform="translate(2043 4367)" fill="#1B1F23"/>
          </g>
      </svg>
      </div>
      <div class="nav-close-icon" @click="closeNav()" v-bind:class="{nav_icon_close_opened: this.showNav}">
        <svg xmlns="http://www.w3.org/2000/svg" width="30" height="80" viewBox="0 0 173.282 173.282">
  <g id="Group_43" data-name="Group 43" transform="translate(-1956.718 -4482)">
    <rect id="Rectangle_59" data-name="Rectangle 59" width="212.754" height="32.303" rx="16.151" transform="translate(1979.56 4482) rotate(45)" fill="#1b1f23"/>
    <rect id="Rectangle_60" data-name="Rectangle 60" width="212.754" height="32.303" rx="16.152" transform="translate(2130 4504.841) rotate(135)" fill="#1b1f23"/>
  </g>
</svg>

      </div>
      <div class="links" @click="closeNav()" v-bind:class="{nav_open: this.showNav}">
        <router-link to="/" class="link">Home</router-link>
        <router-link to="/about" class="link">Über uns</router-link>
        <router-link to="/privacy" class="link">Datenschutz</router-link>
        <div id="signup-button" class="link">
          <router-link to="/signup">Hol dir die App</router-link>
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

/*@font-face {
  font-family: "cera-pro";
  src: url("./assets/fonts/cera-light.otf");
  font-style: normal;
  font-weight: 300;
}

@font-face {
  font-family: "cera-pro";
  src: url("./assets/fonts/cera-medium.otf");
  font-style: normal;
  font-weight: 400;
}
@font-face {
  font-family: "cera-pro";
  src: url("./assets/fonts/cera-bold.otf");
  font-style: normal;
  font-weight: 700;
}

@font-face {
  font-family: "cera-pro";
  src: url("./assets/fonts/cera-black.otf");
  font-style: normal;
  font-weight: 900;
}*/

#app {
  font-family: Gilroy, Helvetiva, sans-serif;
  text-align: center;
  margin: 0;
  color: #1b1f23;
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
  color: #1b1f23;
  font-size: 16px;
  margin: 0 30px;
}

#nav a.router-link-exact-active {
  color: #40caff;
}

#signup-button a {
  background-color: #40caff;
  padding: 12px 35px;
  color: #fff;
  transition: 0.2s ease-in;
  word-wrap: none;
  overflow-wrap: initial;
}
#signup-button a:hover {
  background-color: #1ab5f1;
  transition: 0.2s ease-out;
}
#signup-button a.router-link-exact-active {
  color: #fff;
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
    background-color: rgba(255,255,255,1);
    display: none;
    transition: 0.2s ease-out;
    -webkit-box-shadow: 0px 0px 40px -2px rgba(133,149,168,1);
-moz-box-shadow: 0px 0px 40px -2px rgba(133,149,168,1);
box-shadow: 0px 0px 40px -2px rgba(133,149,168,1);
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
