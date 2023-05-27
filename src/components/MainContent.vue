<template>
    <div class="row justify-content-center">
        <div class="col-md-auto">
            <img alt="sofia_h" src="./../assets/IMG_0572.jpg" width="120"/>
            <h2 class="grad-text">Sofia Haglund</h2>
            <p>Bioinformatician<i class="bx bx-fw bx-code bx-sm"></i>System Developer</p>
            <hr>
            <p class="know" style="font-size:1rem">I know</p>
            <i class="bx bx-fw bx-down-arrow-alt bx-sm bx-tada"></i>
        </div>
    </div>
</template>

<style scoped>

h2 {
  font-family: Bubblegum Sans;
  -webkit-text-stroke: 1px black;
}

p {
  font-family: Roboto;
}

img {
  border: 1px solid #000000;
  border-radius: 100%;
}

img:hover {
  filter: gray;
  -webkit-filter: grayscale(1);
}

.grad-text {
  background-image: linear-gradient(to right, rgb(255, 168, 239), rgb(137, 186, 202), #bd7fcc);
  background-size: 100%;
  -webkit-background-clip: text;
  background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}

.grad-text:hover {
  background-image: linear-gradient(to right, rgb(137, 186, 202), #bd7fcc, rgb(255, 168, 239));
    
}

@media (min-width: 1281px) {

  .col-md-auto {
    margin-top: 3%;
  }

  h2 {
    margin-top: 5%;
    font-size: 7rem;
  }

  p {
    font-size: 1.5rem;
  }
}

@media (min-width: 768px) and (max-width: 1280px) {

  .col-md-auto {
    margin-top: 25%;
  }

  h2 {
    margin-top: 5%;
    font-size: 7rem;
  }

  p {
    font-size: 1.8rem;
    margin-top: 5%;
  }
}

@media (min-width: 768px) and (max-width: 1280px) {

  .know {
    margin-top: 50%;
  }
}

@media (max-width: 767px) {

  .col-md-auto {
    margin-top: 15%;
  }

  h2 {
    margin-top: 5%;
    font-size: 4rem;
  }

  p {
    font-size: 1rem;
  }

  .know {
    margin-top: 20%;
  }
}

</style>