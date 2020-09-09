<template>
  <div class="footer">
    <img id="logo" src="../assets/ehrenapp-logo.png" alt="Logo">
    <div id="footer-content">
      <table id="footer-links">
        <tr>
          <td>
            <router-link to="/">Home</router-link>
          </td>
          <!--<td>
            <router-link to="/about">Privacy</router-link>
          </td>-->
        </tr>
        <tr>
          <td>
            <router-link to="/privacy">Datenschutz</router-link>
          </td>
        </tr>
      </table>
    </div>
    
    <div id="footer-bottom">
      <h3>© EhrenApp GmbH 2020</h3>
      <div id="social-media">
        <a href="https://www.instagram.com/ehren.app" class="social-media-link" target="_blank">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 81.577 81.558">
          <path
            id="Icon_awesome-instagram"
            data-name="Icon awesome-instagram"
            d="M40.792,22.106A20.911,20.911,0,1,0,61.7,43.017,20.877,20.877,0,0,0,40.792,22.106Zm0,34.505A13.595,13.595,0,1,1,54.387,43.017,13.619,13.619,0,0,1,40.792,56.611Zm26.643-35.36a4.877,4.877,0,1,1-4.877-4.877A4.866,4.866,0,0,1,67.435,21.251ZM81.285,26.2c-.309-6.533-1.8-12.321-6.588-17.089-4.768-4.768-10.555-6.26-17.089-6.588-6.734-.382-26.916-.382-33.65,0-6.515.309-12.3,1.8-17.089,6.57S.609,19.649.281,26.183C-.1,32.916-.1,53.1.281,59.833c.309,6.533,1.8,12.321,6.588,17.089s10.555,6.26,17.089,6.588c6.734.382,26.916.382,33.65,0,6.533-.309,12.321-1.8,17.089-6.588,4.768-4.768,6.26-10.555,6.588-17.089.382-6.734.382-26.9,0-33.632Zm-8.7,40.857a13.763,13.763,0,0,1-7.753,7.753c-5.369,2.129-18.108,1.638-24.041,1.638s-18.69.473-24.041-1.638A13.763,13.763,0,0,1,9,67.058C6.869,61.689,7.361,48.95,7.361,43.017S6.888,24.327,9,18.976a13.763,13.763,0,0,1,7.753-7.753C22.12,9.094,34.859,9.585,40.792,9.585s18.69-.473,24.041,1.638a13.763,13.763,0,0,1,7.753,7.753c2.129,5.369,1.638,18.108,1.638,24.041S74.715,61.707,72.586,67.058Z"
            transform="translate(0.005 -2.238)"
            fill="#626C79"
          />
        </svg>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
  components: {}
};
</script>

<style scoped>
.footer {
  height: 300px;
  background-color: #161616;
  padding: 5% 15%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: space-between;
}
#logo{
  width: 150px;
}
#footer-content {
  width: 100%;
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  align-items: center;
}

#footer-links {
  margin-top: 2%;
  min-width: 300px;
}
#footer-links td {
  width: 200px;
  text-align: left;
}
#footer-links tr {
  height: 35px;
}
#footer-links a {
  margin: 20px 0;
  text-decoration: none;
  text-transform: uppercase;
  font-family: Gilroy, Helvetica, sans-serif;
  color:#626C79;
  font-weight: 800;
  font-size: 14px;
  letter-spacing: 1px;
}


#footer-bottom {
  margin-top: 3%;
  width: 50%;
  min-width: 350px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
#footer-bottom h3 {
  color: #626C79;
  font-size: 14px;
  font-weight: 300;
}
#social-media {
  margin: 0 2%;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
@media screen and (max-width: 1280px) {
  .footer {
    padding: 10% 5%;
    justify-content: space-between;
  }
 

#footer-links {
  width: 100%;
  min-width: 0px;
}
#footer-bottom {
  width: 100%;
  min-width: 0px;
}

}
</style>
