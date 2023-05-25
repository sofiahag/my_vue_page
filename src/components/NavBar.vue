<template>
    <div class="row justify-content-center">
      <div class="col-lg-2 col-sm-3 uni">
        <img alt="by catalyststuff on Freepik" src="./../assets/7300_1_10_3.png" width="60"/>
       </div>
       <div class="col-lg-2 col-sm-3 logo">
        <a class="logo-text" href="https://github.com/sofiahag">GitHub</a><a href="https://github.com/sofiahag"><i class="bx bx-fw bxl-github bx-sm"></i></a>
       </div>
       <div class="col-lg-2 col-sm-3 logo">
        <a class="logo-text" href="https://www.linkedin.com/in/sofia-haglund-6939a8160/">Linkedin</a><a href="https://www.linkedin.com/in/sofia-haglund-6939a8160/"><i class="bx bx-fw bxl-linkedin bx-sm"></i></a>
       </div>
       <div class="col-lg-2 col-sm-3 logo">
        <a class="logo-text" href="https://ngisweden.scilifelab.se/">NGI</a><a href="https://ngisweden.scilifelab.se/"><i class="bx bx-fw bx-dna bx-sm"></i></a>
       </div>
       <div class="col-lg-2 col-sm-3 logo">
        <a class="logo-text" href="https://www.youtube.com/channel/UCkOM8G7wEJKloyYT6sIo63w">Youtube</a><a href="https://www.youtube.com/channel/UCkOM8G7wEJKloyYT6sIo63w"><i class="bx bx-fw bxl-youtube bx-sm"></i></a>
       </div>
       <div class="col-lg-2 col-sm-3 uni flip">
        <img alt="by catalyststuff on Freepik" src="./../assets/7300_1_10_3.png" width="60"/>
       </div>
    </div>
    <hr>
</template>

<style scoped>

a {
  color: black;
  text-decoration: none;
  background:
    linear-gradient(
      to right,
      white,
      white
    ),
    linear-gradient(
      to right,
      rgb(119, 205, 239),
      rgb(224, 96, 244),
      rgb(245, 110, 211)
  );
  background-size: 100% 3px, 0 3px;
  background-position: 100% 100%, 0 100%;
  background-repeat: no-repeat;
  transition: background-size 400ms;
}

a:hover {
  background-size: 0 3px, 100% 3px;
}

.flip {
  -webkit-transform: scaleX(-1);
  transform: scaleX(-1);
}

@media (min-width: 1281px) {

  .col-lg-2 {
    float: left;
    width: 16%;
  }

  .uni {
    margin-top: 1%;
  }
  .logo {
    margin-top: 2%;
  }
}

@media (min-width: 768px) and (max-width: 1280px) {

  .col-lg-2 {
    float: left;
    width: 16%;
  }

  .uni {
    margin-top: 1%;
  }
  .logo {
    margin-top: 3%;
  }
}

@media (max-width: 767px) {

  .col-sm-3 {
    float: left;
    width: 25%;
    margin-top: 3%;
  }

  .uni {
    display: none;
  }

  .logo-text {
    display: none;
  }
}

</style>