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
          <h5 class="mb-2 text-3xl font-bold text-center tracking-tight text-gray-900 dark:text-gray">DAFTAR PRODUK KAMI</h5>
          <br>
          <br>
<div class="grid grid-cols-2 gap-2">
        <div>
          <the-card href="#" variant="vertical" img-src="https://sementigaroda.com/data-str/images/posts/2020/09/23/609/merk-semen-terbaik.jpg" img-alt="Desk">
 <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Semen Tiga Roda</h5>
 <p class="font-normal text-gray-700 dark:text-gray-400">
 </p>
          </the-card>
          </div>
          <div>
          <the-card href="#" variant="vertical" img-src="https://blue.kumparan.com/image/upload/fl_progressive,fl_lossy,c_fill,q_auto:best,w_640/v1642848023/a4wd7otnfyfxomou7cxl.jpg
" img-alt="Desk">
<br>
 <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Tukang Bangunan</h5>
 <p class="font-normal text-gray-700 dark:text-gray-400">
 </p>
          </the-card>
          </div>
          <div>
            <the-card href="#" variant="vertical" img-src="https://berita.99.co/wp-content/uploads/2019/10/tool-box-lengkap.jpg
" img-alt="Desk">
 <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Peralatan Bangunan</h5>
 <p class="font-normal text-gray-700 dark:text-gray-400">
 </p>
          </the-card>
          </div>
       <div>
        <the-card href="#" variant="vertical" img-src="https://i0.wp.com/www.builder.id/wp-content/uploads/2019/10/peralatan-bangunan-penting.jpg?fit=600%2C350&ssl=1
" img-alt="Desk">
<br>
<br>
 <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Peralatan Bangunan</h5>
 <p class="font-normal text-gray-700 dark:text-gray-400">
 </p>
          </the-card>
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