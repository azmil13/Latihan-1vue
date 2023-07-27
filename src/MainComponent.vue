<template>
    <div class="main">
      <section id="layanan">
          <center>
            <h1 class="layanankami">Layanan Kami</h1>
          </center>
          <div class="flex flex-row mx-auto place-content-center gap-6 mt-7">
            <div class="basis-1/5">
              <the-card href="#">
                <i class="fa-solid fa-industry"></i>
                <h5
                  class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white"
                >
                  Produk Semen Negeri
                </h5>
      
                <p class="font-normal text-gray-700 dark:text-gray-400">
                  Kami menyediakan semen yang berkualitas dan harga yang terjangkau
                </p>
              </the-card>
            </div>
            <div class="basis-1/5">
              <the-card href="#">
                <i class="fa-solid fa-city"></i>
                <h5
                  class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">
                  Tukang Bangunan 
                </h5>
                <p class="font-normal text-gray-700 dark:text-gray-400">
                  Kami Bisa Menjadi Tukang Bangunan 
                </p>
              </the-card>
            </div>
            <div class="basis-1/5">
              <the-card href="#">
                <i class="fa-solid fa-gears"></i>
                <h5
                  class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white"
                >
                  Produk Alat Alat Bangunan 
                </h5>
                <p class="font-normal text-gray-700 dark:text-gray-400">
                  Kami Menyediakan Alat-Alat Bangunan Berupa Pacul Ember Dan Lain-Lain
                </p>
              </the-card>
            </div>
          </div>
          <br>
          <br>
          <br>
          <br>
          <center>
            <h1 class="layanankami">Produk Semen</h1>
          </center>
          <div class="grid grid-cols-2 gap-2">
        <div>
            <img class="h-auto max-w-full rounded-lg" src="./assets/logosemen.jpg" height="250" width="300">
        </div>
        <div>
            <img class="h-auto max-w-full rounded-lg" src="https://scgcbm.id/wp-content/uploads/2021/12/Packshot-Semen-SCG_Front-40KG-edit.png" height="250" width="300">
        </div>
        <div>
            <center><img class="h-auto max-w-full rounded-lg" src="https://semenmerahputih.com/images/pcc.png" height="250" width="300">
              </center>
        </div>
    </div>
    <br>
    <br>
    <br>
    <br>
    <br>
          <center>
            <h1 class="layanankami">Tukang Bangunan</h1>
          </center>
    <div class="grid grid-cols-2 gap-2">
        <div>
            <img class="h-auto max-w-full rounded-lg" src="https://png.pngtree.com/png-clipart/20221216/original/pngtree-engineer-architect-and-builder-mason-at-construction-site-png-image_8750971.png" height="250" width="300">
        </div>
        <div>
            <img class="h-auto max-w-full rounded-lg" src="https://siplahtelkom.com/public/products/164909/3454839/5443bc95-3c43-4.1649759080.jpg" height="250" width="300">
        </div>
        <div> <center> 
            <img class="h-auto max-w-full rounded-lg" src="https://univerbuild.com/wp-content/uploads/2020/06/Jasa-Tukang-Bangunan-Jogja.png" height="250" width="300">
            </center>
        </div>
    </div>
    <br>
    <br>
    <br>
    <br>
    <br>
    <center>
            <h1 class="layanankami">Peralatan bangunan</h1>
          </center>
    <div class="grid grid-cols-2 gap-2">
        <div>
            <img class="h-auto max-w-full rounded-lg" src="https://i0.wp.com/www.builder.id/wp-content/uploads/2019/10/peralatan-bangunan-penting.jpg?fit=600%2C350&ssl=1" height="250" width="300">
        </div>
        <div>
            <img class="h-auto max-w-full rounded-lg" src="https://media.istockphoto.com/id/135902580/id/foto/lingkaran-alat-bangunan-di-belakang-pisau-gergaji-dan-papan-kayu.jpg?s=1024x1024&w=is&k=20&c=I06K6c9PVCG9C_6Daca9bLwxY0zt3sx-zhGkSyaqI18=" height="250" width="300">
        </div>
        <div><center> 
            <img class="h-auto max-w-full rounded-lg" src="https://banamitra.com/wp-content/uploads/2020/10/alat-tukang-bangunan.jpg" height="250" width="300">
            </center>
        </div>
    </div>

      </section>
      <section id="tentang">
          <center>
            <div class="flex flex-row mx-auto place-content-center">
              <div class="basis-1/2">
                <img
                  src="https://o.remove.bg/downloads/35abebb3-7e00-4b97-8c80-bad5e046a7a0/istockphoto-1214970249-170667a-removebg-preview.png"
                  width="300"
                  alt=""
                />
              </div>
              <div class="basis-1/2">
                <br>
                <br>
              </div>
            </div>
          </center>
      </section>
    </div>
  </template>
  
  <script setup>
  import { TheCard } from 'flowbite-vue';
  </script>
  
  <style>
  .layanankami {
    font-family: 'Montserrat', sans-serif;
    font-size: 38px;
    font-weight: bold;
  }
  .fa-solid {
    font-size: 30px;
  }
  </style>