<template>
  <div>
    <Navbar />

    <!-- Section Hero -->
    <section class="section--hero mb--section">
      <div class="container-fluid container-lg">
        <!-- Small Devices -->
        <div class="d-block d-lg-none">
          <div class="d-flex flex-column justify-content-center align-items-center">
            <img src="~/assets/images/hero-1.png" class="img-fluid my-5" alt="">
            <div>
              <h1 class="hero--title text-center text-lg-start">SEMI<span>KODE</span></h1>
              <h2 class="hero--subtitle text-center text-lg-start mb-4">
                IT Solution & Digital Agency siap membantu bisnis Anda menjadi lebih mudah dikelola
              </h2>
              <div class="d-flex justify-content-center mb-5">
                <button class="btn btn--outline-crayola btn--contant-us">
                  Hubungi Kami&emsp;<i class="fa-solid fa-paper-plane"></i>
                </button>
              </div>
            </div>
          </div>
        </div>

        <!-- Large Device -->
        <div class="d-none d-lg-block">
          <div class="row">
            <div class="col-12 col-lg-6">
              <div class="h-100 d-flex align-items-center">
                <div>
                  <h1 class="hero--title text-center text-lg-start">SEMI<span>KODE</span></h1>
                  <h2 class="hero--subtitle text-center text-lg-start mb-4">
                    IT Solution & Digital Agency siap membantu bisnis Anda menjadi lebih mudah dikelola
                  </h2>
                  <div class="d-flex">
                    <button class="btn btn--outline-crayola btn--contant-us">
                      Hubungi Kami&emsp;<i class="fa-solid fa-paper-plane"></i>
                    </button>
                  </div>
                </div>
              </div>
            </div>
            <div class="col-12 col-lg-6">
              <div class="h-100 d-flex justify-content-center align-items-center ">
                <img src="~/assets/images/hero-1.png" class="img-fluid mt-5" alt="">
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- End Section Hero -->

    <!-- Section About Us -->
    <section class="section--about-us mb--section">
      <div class="container-fluid container-lg">
        <!-- Small Devices -->
        <div class="d-block d-lg-none">
          <div class="d-flex flex-column justify-content-center align-items-center">
            <h2 class="section--title text-center text-lg-start mb-5">Tentang <span>Kami</span></h2>
            <img src="~/assets/images/hero-2.png" class="img-fluid mb-5" alt="">
            <p class="text--justify">
              SEMIKODE merupakan tim freelancer yang bergerak di bidang Digital Agency yang bertempat di kota
              tegal. Kami selalu memberikan yang terbaik kepada klien kami. Sudah banyak project yang sudah
              kami selesaikan. Terima kasih sudah mempercayakan kami dalam menyelesaikan masalah dalam
              kebutuhan bisnis Anda.
            </p>
          </div>
        </div>

        <!-- Large Device -->
        <div class="d-none d-lg-block">
          <div class="row">
            <div class="col-12 col-lg-6">
              <div class="h-100 d-flex justify-content-center align-items-center">
                <img src="~/assets/images/hero-2.png" class="img-fluid" alt="">
              </div>
            </div>
            <div class="col-12 col-lg-6">
              <div class="h-100 d-flex align-items-center">
                <div>
                  <h2 class="section--title text-center text-lg-start">Tentang <span>Kami</span></h2>
                  <p class="">
                    SEMIKODE merupakan tim freelancer yang bergerak di bidang Digital Agency yang
                    bertempat di kota tegal. Kami selalu memberikan yang terbaik kepada klien kami.
                    Sudah banyak project yang sudah kami selesaikan. Terima kasih sudah mempercayakan
                    kami dalam menyelesaikan masalah dalam kebutuhan bisnis Anda.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- End Section About Us -->

    <!-- Section Service -->
    <section class="section--service mb--section">
        <div class="container-fluid container-lg">
            <h2 class="section--title text-center">
                Layanan <span>Kami</span>
            </h2>
            <!-- Small Devices -->
            <div class="d-block d-lg-none">
                <p class="text-center mb-5 px-2 px-lg-0">
                    Kami menyediakan beberapa layanan yang dapat membantu bisnis Anda go Online
                </p>
            </div>
            <!-- Large Devices -->
            <div class="d-none d-lg-block">
                <div class="w-50 mx-auto">
                    <p class="text-center mb-5">
                        Kami menyediakan beberapa layanan yang dapat membantu bisnis Anda go Online
                    </p>
                </div>
            </div>

            <!-- Slider main container -->
            <div class="swiper swiper--service">
                <!-- Additional required wrapper -->
                <div class="swiper-wrapper">
                    <div class="swiper-slide">
                        <div class="card card--custome mb-3">
                            <img src="~/assets/images/service-1.png" class="card-img-top" alt="Layanan Website">
                            <div class="card-body">
                                <h5 class="card-title">Pembuatan Website</h5>
                                <p class="card-text">Kami akan membantu Anda membuat website Company Profile, POS,
                                    Warehouse, E-Commerce, E-Learning, E-Voting, dll.</p>
                            </div>
                        </div>
                    </div>
                    <div class="swiper-slide">
                        <div class="card card--custome mb-3">
                            <img src="~/assets/images/service-2.png" class="card-img-top" alt="Layanan Website">
                            <div class="card-body">
                                <h5 class="card-title">Aplikasi Android</h5>
                                <p class="card-text">Kami akan membantu Anda membuat Aplikasi Android untuk bisnis,
                                    sekolah,
                                    organisasi, dll.</p>
                            </div>
                        </div>
                    </div>
                    <div class="swiper-slide">
                        <div class="card card--custome mb-3">
                            <img src="~/assets/images/service-3.png" class="card-img-top" alt="Layanan Website">
                            <div class="card-body">
                                <h5 class="card-title">Pembuatan UI/UX</h5>
                                <p class="card-text">Kami akan membantu Anda merancang website yang akan dibuat dengan
                                    wireframing, mockup design dll.</p>
                            </div>
                        </div>
                    </div>
                    <div class="swiper-slide">
                        <div class="card card--custome mb-3">
                            <img src="~/assets/images/service-4.png" class="card-img-top" alt="Layanan Website">
                            <div class="card-body">
                                <h5 class="card-title">Desain Feed Instagram </h5>
                                <p class="card-text">Kami akan membantu Anda membuat feed instagram jadi lebih menarik
                                    dengan desain yang kami buat.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- End Section Service -->

    <!-- Section Portfolio -->
    <section class="section--portfolio mb--section">
        <div class="container-fluid container-lg">
            <h2 class="section--title text-center">
                Portfolio <span>Kami</span>
            </h2>
            <!-- Small Devices -->
            <div class="d-block d-lg-none">
                <p class="text-center mb-5 px-2 px-lg-0">
                    Kami telah membantu berbagai perusahaan yang bergerak di bidang e-commerce, UMKM, ekspor, dll.
                </p>
            </div>
            <!-- Large Devices -->
            <div class="d-none d-lg-block">
                <div class="w-50 mx-auto">
                    <p class="text-center mb-5">
                        Kami telah membantu berbagai perusahaan yang bergerak di bidang e-commerce, UMKM, ekspor, dll.
                    </p>
                </div>
            </div>

            <div class="tablinks mb-5">
                <ul class="nav col-12 col-md-auto mb-2 justify-content-center mb-md-0">
                    <li>
                        <a class="nav-link tab--link px-2 mx-lg-3" @click="toggleTabs(1)" :class="{ active: openTab == 1 }">Website</a>
                    </li>
                    <li>
                        <a class="nav-link tab--link px-2 mx-lg-3" @click="toggleTabs(2)" :class="{ active: openTab == 2 }">Android</a>
                    </li>
                    <li>
                        <a class="nav-link tab--link px-2 mx-lg-3" @click="toggleTabs(3)" :class="{ active: openTab == 3 }">Graphic Design</a>
                    </li>
                    <li>
                        <a class="nav-link tab--link px-2 mx-lg-3" @click="toggleTabs(4)" :class="{ active: openTab == 4 }">UI/UX</a>
                    </li>
                </ul>
            </div>

            <div class="tabcontents">
                <div id="website" class="tabcontent" v-bind:class="{'d-none': openTab !== 1, 'd-block': openTab === 1}">
                    <div class="d-block d-lg-none">
                        <div class="swiper swiper--portfolio-website">
                            <div class="swiper-wrapper">
                                <div class="swiper-slide">
                                    <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                        <div class="content-overlay"></div>
                                        <img src="~/assets/images/travelme.png" class="card-img-top card--image-custom"
                                            alt="TravelMe">
                                        <div class="card-body">
                                            <h2 class="card-title text-center mb-3">Travelme</h2>
                                        </div>
                                        <div class="content-details">
                                            <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                                <i class="fa-solid fa-globe"></i>
                                            </div>
                                            <a href="#" class="link--portfolio">Lihat Website</a>
                                        </div>
                                    </div>
                                </div>
                                <div class="swiper-slide">
                                    <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                        <div class="content-overlay"></div>
                                        <img src="~/assets/images/apotek.png" class="card-img-top card--image-custom"
                                            alt="E-Apotek">
                                        <div class="card-body">
                                            <h2 class="card-title text-center mb-3">E-Apotek</h2>
                                        </div>
                                        <div class="content-details">
                                            <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                                <i class="fa-solid fa-globe"></i>
                                            </div>
                                            <a href="#" class="link--portfolio">Lihat Website</a>
                                        </div>
                                    </div>
                                </div>
                                <div class="swiper-slide">
                                    <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                        <div class="content-overlay"></div>
                                        <img src="~/assets/images/agroedufarm.png" class="card-img-top card--image-custom"
                                            alt="AgroEduFarm">
                                        <div class="card-body">
                                            <h2 class="card-title text-center mb-3">AgroEduFarm</h2>
                                        </div>
                                        <div class="content-details">
                                            <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                                <i class="fa-solid fa-globe"></i>
                                            </div>
                                            <a href="#" class="link--portfolio">Lihat Website</a>
                                        </div>
                                    </div>
                                </div>
                                <div class="swiper-slide">
                                    <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                        <div class="content-overlay"></div>
                                        <img src="~/assets/images/alko.png" class="card-img-top card--image-custom"
                                            alt="Alko Sumatera">
                                        <div class="card-body">
                                            <h2 class="card-title text-center mb-3">Alko Sumatera</h2>
                                        </div>
                                        <div class="content-details">
                                            <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                                <i class="fa-solid fa-globe"></i>
                                            </div>
                                            <a href="#" class="link--portfolio">Lihat Website</a>
                                        </div>
                                    </div>
                                </div>
                                <div class="swiper-slide">
                                    <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                        <div class="content-overlay"></div>
                                        <img src="~/assets/images/alkoadmin.png" class="card-img-top card--image-custom"
                                            alt="Alko Admin">
                                        <div class="card-body">
                                            <h2 class="card-title text-center mb-3">Alko Admin</h2>
                                        </div>
                                        <div class="content-details">
                                            <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                                <i class="fa-solid fa-globe"></i>
                                            </div>
                                            <a href="#" class="link--portfolio">Lihat Website</a>
                                        </div>
                                    </div>
                                </div>
                                <div class="swiper-slide">
                                    <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                        <div class="content-overlay"></div>
                                        <img src="~/assets/images/alkopos.png" class="card-img-top card--image-custom"
                                            alt="alkopos">
                                        <div class="card-body">
                                            <h2 class="card-title text-center mb-3">Alko Point of Sales</h2>
                                        </div>
                                        <div class="content-details">
                                            <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                                <i class="fa-solid fa-globe"></i>
                                            </div>
                                            <a href="#" class="link--portfolio">Lihat Website</a>
                                        </div>
                                    </div>
                                </div>
                                <div class="swiper-slide">
                                    <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                        <div class="content-overlay"></div>
                                        <img src="~/assets/images/birdnest.png" class="card-img-top card--image-custom"
                                            alt="Birdnest">
                                        <div class="card-body">
                                            <h2 class="card-title text-center mb-3">Bird's Nest Dundee</h2>
                                        </div>
                                        <div class="content-details">
                                            <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                                <i class="fa-solid fa-globe"></i>
                                            </div>
                                            <a href="#" class="link--portfolio">Lihat Website</a>
                                        </div>
                                    </div>
                                </div>
                                <div class="swiper-slide">
                                    <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                        <div class="content-overlay"></div>
                                        <img src="~/assets/images/twentypicture.png"
                                            class="card-img-top card--image-custom" alt="Twenty Picture">
                                        <div class="card-body">
                                            <h2 class="card-title text-center mb-3">Twenty Picture</h2>
                                        </div>
                                        <div class="content-details">
                                            <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                                <i class="fa-solid fa-globe"></i>
                                            </div>
                                            <a href="#" class="link--portfolio">Lihat Website</a>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="d-none d-lg-block">
                        <div class="row">
                            <div class="col-12 col-lg-3">
                                <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                    <div class="content-overlay"></div>
                                    <img src="~/assets/images/travelme.png" class="card-img-top card--image-custom"
                                        alt="TravelMe">
                                    <div class="card-body">
                                        <h2 class="card-title text-center mb-3">Travelme</h2>
                                    </div>
                                    <div class="content-details">
                                        <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                            <i class="fa-solid fa-globe"></i>
                                        </div>
                                        <a href="#" class="link--portfolio">Lihat Website</a>
                                    </div>
                                </div>
                            </div>
                            <div class="col-12 col-lg-3">
                                <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                    <div class="content-overlay"></div>
                                    <img src="~/assets/images/apotek.png" class="card-img-top card--image-custom"
                                        alt="E-Apotek">
                                    <div class="card-body">
                                        <h2 class="card-title text-center mb-3">E-Apotek</h2>
                                    </div>
                                    <div class="content-details">
                                        <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                            <i class="fa-solid fa-globe"></i>
                                        </div>
                                        <a href="#" class="link--portfolio">Lihat Website</a>
                                    </div>
                                </div>
                            </div>
                            <div class="col-12 col-lg-3">
                                <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                    <div class="content-overlay"></div>
                                    <img src="~/assets/images/agroedufarm.png" class="card-img-top card--image-custom"
                                        alt="AgroEduFarm">
                                    <div class="card-body">
                                        <h2 class="card-title text-center mb-3">AgroEduFarm</h2>
                                    </div>
                                    <div class="content-details">
                                        <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                            <i class="fa-solid fa-globe"></i>
                                        </div>
                                        <a href="#" class="link--portfolio">Lihat Website</a>
                                    </div>
                                </div>
                            </div>
                            <div class="col-12 col-lg-3">
                                <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                    <div class="content-overlay"></div>
                                    <img src="~/assets/images/alko.png" class="card-img-top card--image-custom"
                                        alt="Alko Sumatera">
                                    <div class="card-body">
                                        <h2 class="card-title text-center mb-3">Alko Sumatera</h2>
                                    </div>
                                    <div class="content-details">
                                        <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                            <i class="fa-solid fa-globe"></i>
                                        </div>
                                        <a href="#" class="link--portfolio">Lihat Website</a>
                                    </div>
                                </div>
                            </div>
                            <div class="col-12 col-lg-3">
                                <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                    <div class="content-overlay"></div>
                                    <img src="~/assets/images/alkoadmin.png" class="card-img-top card--image-custom"
                                        alt="Alko Admin">
                                    <div class="card-body">
                                        <h2 class="card-title text-center mb-3">Alko Admin</h2>
                                    </div>
                                    <div class="content-details">
                                        <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                            <i class="fa-solid fa-globe"></i>
                                        </div>
                                        <a href="#" class="link--portfolio">Lihat Website</a>
                                    </div>
                                </div>
                            </div>
                            <div class="col-12 col-lg-3">
                                <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                    <div class="content-overlay"></div>
                                    <img src="~/assets/images/alkopos.png" class="card-img-top card--image-custom"
                                        alt="alkopos">
                                    <div class="card-body">
                                        <h2 class="card-title text-center mb-3">Alko Point of Sales</h2>
                                    </div>
                                    <div class="content-details">
                                        <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                            <i class="fa-solid fa-globe"></i>
                                        </div>
                                        <a href="#" class="link--portfolio">Lihat Website</a>
                                    </div>
                                </div>
                            </div>
                            <div class="col-12 col-lg-3">
                                <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                    <div class="content-overlay"></div>
                                    <img src="~/assets/images/birdnest.png" class="card-img-top card--image-custom"
                                        alt="Birdnest">
                                    <div class="card-body">
                                        <h2 class="card-title text-center mb-3">Bird's Nest Dundee</h2>
                                    </div>
                                    <div class="content-details">
                                        <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                            <i class="fa-solid fa-globe"></i>
                                        </div>
                                        <a href="#" class="link--portfolio">Lihat Website</a>
                                    </div>
                                </div>
                            </div>
                            <div class="col-12 col-lg-3">
                                <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                    <div class="content-overlay"></div>
                                    <img src="~/assets/images/twentypicture.png" class="card-img-top card--image-custom"
                                        alt="Twenty Picture">
                                    <div class="card-body">
                                        <h2 class="card-title text-center mb-3">Twenty Picture</h2>
                                    </div>
                                    <div class="content-details">
                                        <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                            <i class="fa-solid fa-globe"></i>
                                        </div>
                                        <a href="#" class="link--portfolio">Lihat Website</a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div id="android" class="tabcontent" v-bind:class="{'d-none': openTab !== 2, 'd-block': openTab === 2}">
                    <div class="d-block d-lg-none">
                        <div class="swiper swiper--portfolio-website">
                            <div class="swiper-wrapper">
                                <div class="swiper-slide">
                                    <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                        <div class="content-overlay"></div>
                                        <img src="~/assets/images/alko.png" class="card-img-top card--image-custom"
                                            alt="Alko Sumatera">
                                        <div class="card-body">
                                            <h2 class="card-title text-center mb-3">Alko Sumatera</h2>
                                        </div>
                                        <div class="content-details">
                                            <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                                <i class="fa-solid fa-globe"></i>
                                            </div>
                                            <a href="#" class="link--portfolio">Lihat Website</a>
                                        </div>
                                    </div>
                                </div>
                                <div class="swiper-slide">
                                    <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                        <div class="content-overlay"></div>
                                        <img src="~/assets/images/alkoadmin.png" class="card-img-top card--image-custom"
                                            alt="Alko Admin">
                                        <div class="card-body">
                                            <h2 class="card-title text-center mb-3">Alko Admin</h2>
                                        </div>
                                        <div class="content-details">
                                            <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                                <i class="fa-solid fa-globe"></i>
                                            </div>
                                            <a href="#" class="link--portfolio">Lihat Website</a>
                                        </div>
                                    </div>
                                </div>
                                <div class="swiper-slide">
                                    <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                        <div class="content-overlay"></div>
                                        <img src="~/assets/images/alkopos.png" class="card-img-top card--image-custom"
                                            alt="alkopos">
                                        <div class="card-body">
                                            <h2 class="card-title text-center mb-3">Alko Point of Sales</h2>
                                        </div>
                                        <div class="content-details">
                                            <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                                <i class="fa-solid fa-globe"></i>
                                            </div>
                                            <a href="#" class="link--portfolio">Lihat Website</a>
                                        </div>
                                    </div>
                                </div>
                                <div class="swiper-slide">
                                    <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                        <div class="content-overlay"></div>
                                        <img src="~/assets/images/birdnest.png" class="card-img-top card--image-custom"
                                            alt="Birdnest">
                                        <div class="card-body">
                                            <h2 class="card-title text-center mb-3">Bird's Nest Dundee</h2>
                                        </div>
                                        <div class="content-details">
                                            <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                                <i class="fa-solid fa-globe"></i>
                                            </div>
                                            <a href="#" class="link--portfolio">Lihat Website</a>
                                        </div>
                                    </div>
                                </div>
                                <div class="swiper-slide">
                                    <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                        <div class="content-overlay"></div>
                                        <img src="~/assets/images/twentypicture.png"
                                            class="card-img-top card--image-custom" alt="Twenty Picture">
                                        <div class="card-body">
                                            <h2 class="card-title text-center mb-3">Twenty Picture</h2>
                                        </div>
                                        <div class="content-details">
                                            <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                                <i class="fa-solid fa-globe"></i>
                                            </div>
                                            <a href="#" class="link--portfolio">Lihat Website</a>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="d-none d-lg-block">
                        <div class="row">
                            <div class="col-12 col-lg-3">
                                <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                    <div class="content-overlay"></div>
                                    <img src="~/assets/images/alko.png" class="card-img-top card--image-custom"
                                        alt="Alko Sumatera">
                                    <div class="card-body">
                                        <h2 class="card-title text-center mb-3">Alko Sumatera</h2>
                                    </div>
                                    <div class="content-details">
                                        <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                            <i class="fa-solid fa-globe"></i>
                                        </div>
                                        <a href="#" class="link--portfolio">Lihat Website</a>
                                    </div>
                                </div>
                            </div>
                            <div class="col-12 col-lg-3">
                                <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                    <div class="content-overlay"></div>
                                    <img src="~/assets/images/alkoadmin.png" class="card-img-top card--image-custom"
                                        alt="Alko Admin">
                                    <div class="card-body">
                                        <h2 class="card-title text-center mb-3">Alko Admin</h2>
                                    </div>
                                    <div class="content-details">
                                        <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                            <i class="fa-solid fa-globe"></i>
                                        </div>
                                        <a href="#" class="link--portfolio">Lihat Website</a>
                                    </div>
                                </div>
                            </div>
                            <div class="col-12 col-lg-3">
                                <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                    <div class="content-overlay"></div>
                                    <img src="~/assets/images/alkopos.png" class="card-img-top card--image-custom"
                                        alt="alkopos">
                                    <div class="card-body">
                                        <h2 class="card-title text-center mb-3">Alko Point of Sales</h2>
                                    </div>
                                    <div class="content-details">
                                        <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                            <i class="fa-solid fa-globe"></i>
                                        </div>
                                        <a href="#" class="link--portfolio">Lihat Website</a>
                                    </div>
                                </div>
                            </div>
                            <div class="col-12 col-lg-3">
                                <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                    <div class="content-overlay"></div>
                                    <img src="~/assets/images/birdnest.png" class="card-img-top card--image-custom"
                                        alt="Birdnest">
                                    <div class="card-body">
                                        <h2 class="card-title text-center mb-3">Bird's Nest Dundee</h2>
                                    </div>
                                    <div class="content-details">
                                        <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                            <i class="fa-solid fa-globe"></i>
                                        </div>
                                        <a href="#" class="link--portfolio">Lihat Website</a>
                                    </div>
                                </div>
                            </div>
                            <div class="col-12 col-lg-3">
                                <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                    <div class="content-overlay"></div>
                                    <img src="~/assets/images/twentypicture.png" class="card-img-top card--image-custom"
                                        alt="Twenty Picture">
                                    <div class="card-body">
                                        <h2 class="card-title text-center mb-3">Twenty Picture</h2>
                                    </div>
                                    <div class="content-details">
                                        <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                            <i class="fa-solid fa-globe"></i>
                                        </div>
                                        <a href="#" class="link--portfolio">Lihat Website</a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div id="design" class="tabcontent" v-bind:class="{'d-none': openTab !== 3, 'd-block': openTab === 3}">
                    <div class="d-block d-lg-none">
                        <div class="swiper swiper--portfolio-website">
                            <div class="swiper-wrapper">
                                <div class="swiper-slide">
                                    <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                        <div class="content-overlay"></div>
                                        <img src="~/assets/images/alkoadmin.png" class="card-img-top card--image-custom"
                                            alt="Alko Admin">
                                        <div class="card-body">
                                            <h2 class="card-title text-center mb-3">Alko Admin</h2>
                                        </div>
                                        <div class="content-details">
                                            <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                                <i class="fa-solid fa-globe"></i>
                                            </div>
                                            <a href="#" class="link--portfolio">Lihat Website</a>
                                        </div>
                                    </div>
                                </div>
                                <div class="swiper-slide">
                                    <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                        <div class="content-overlay"></div>
                                        <img src="~/assets/images/alkopos.png" class="card-img-top card--image-custom"
                                            alt="alkopos">
                                        <div class="card-body">
                                            <h2 class="card-title text-center mb-3">Alko Point of Sales</h2>
                                        </div>
                                        <div class="content-details">
                                            <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                                <i class="fa-solid fa-globe"></i>
                                            </div>
                                            <a href="#" class="link--portfolio">Lihat Website</a>
                                        </div>
                                    </div>
                                </div>
                                <div class="swiper-slide">
                                    <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                        <div class="content-overlay"></div>
                                        <img src="~/assets/images/birdnest.png" class="card-img-top card--image-custom"
                                            alt="Birdnest">
                                        <div class="card-body">
                                            <h2 class="card-title text-center mb-3">Bird's Nest Dundee</h2>
                                        </div>
                                        <div class="content-details">
                                            <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                                <i class="fa-solid fa-globe"></i>
                                            </div>
                                            <a href="#" class="link--portfolio">Lihat Website</a>
                                        </div>
                                    </div>
                                </div>
                                <div class="swiper-slide">
                                    <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                        <div class="content-overlay"></div>
                                        <img src="~/assets/images/twentypicture.png"
                                            class="card-img-top card--image-custom" alt="Twenty Picture">
                                        <div class="card-body">
                                            <h2 class="card-title text-center mb-3">Twenty Picture</h2>
                                        </div>
                                        <div class="content-details">
                                            <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                                <i class="fa-solid fa-globe"></i>
                                            </div>
                                            <a href="#" class="link--portfolio">Lihat Website</a>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="d-none d-lg-block">
                        <div class="row">
                            <div class="col-12 col-lg-3">
                                <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                    <div class="content-overlay"></div>
                                    <img src="~/assets/images/alkoadmin.png" class="card-img-top card--image-custom"
                                        alt="Alko Admin">
                                    <div class="card-body">
                                        <h2 class="card-title text-center mb-3">Alko Admin</h2>
                                    </div>
                                    <div class="content-details">
                                        <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                            <i class="fa-solid fa-globe"></i>
                                        </div>
                                        <a href="#" class="link--portfolio">Lihat Website</a>
                                    </div>
                                </div>
                            </div>
                            <div class="col-12 col-lg-3">
                                <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                    <div class="content-overlay"></div>
                                    <img src="~/assets/images/alkopos.png" class="card-img-top card--image-custom"
                                        alt="alkopos">
                                    <div class="card-body">
                                        <h2 class="card-title text-center mb-3">Alko Point of Sales</h2>
                                    </div>
                                    <div class="content-details">
                                        <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                            <i class="fa-solid fa-globe"></i>
                                        </div>
                                        <a href="#" class="link--portfolio">Lihat Website</a>
                                    </div>
                                </div>
                            </div>
                            <div class="col-12 col-lg-3">
                                <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                    <div class="content-overlay"></div>
                                    <img src="~/assets/images/birdnest.png" class="card-img-top card--image-custom"
                                        alt="Birdnest">
                                    <div class="card-body">
                                        <h2 class="card-title text-center mb-3">Bird's Nest Dundee</h2>
                                    </div>
                                    <div class="content-details">
                                        <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                            <i class="fa-solid fa-globe"></i>
                                        </div>
                                        <a href="#" class="link--portfolio">Lihat Website</a>
                                    </div>
                                </div>
                            </div>
                            <div class="col-12 col-lg-3">
                                <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                    <div class="content-overlay"></div>
                                    <img src="~/assets/images/twentypicture.png" class="card-img-top card--image-custom"
                                        alt="Twenty Picture">
                                    <div class="card-body">
                                        <h2 class="card-title text-center mb-3">Twenty Picture</h2>
                                    </div>
                                    <div class="content-details">
                                        <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                            <i class="fa-solid fa-globe"></i>
                                        </div>
                                        <a href="#" class="link--portfolio">Lihat Website</a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div id="uiux" class="tabcontent" v-bind:class="{'d-none': openTab !== 4, 'd-block': openTab === 4}">
                    <div class="d-block d-lg-none">
                        <div class="swiper swiper--portfolio-website">
                            <div class="swiper-wrapper">
                                <div class="swiper-slide">
                                    <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                        <div class="content-overlay"></div>
                                        <img src="~/assets/images/alkopos.png" class="card-img-top card--image-custom"
                                            alt="alkopos">
                                        <div class="card-body">
                                            <h2 class="card-title text-center mb-3">Alko Point of Sales</h2>
                                        </div>
                                        <div class="content-details">
                                            <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                                <i class="fa-solid fa-globe"></i>
                                            </div>
                                            <a href="#" class="link--portfolio">Lihat Website</a>
                                        </div>
                                    </div>
                                </div>
                                <div class="swiper-slide">
                                    <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                        <div class="content-overlay"></div>
                                        <img src="~/assets/images/birdnest.png" class="card-img-top card--image-custom"
                                            alt="Birdnest">
                                        <div class="card-body">
                                            <h2 class="card-title text-center mb-3">Bird's Nest Dundee</h2>
                                        </div>
                                        <div class="content-details">
                                            <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                                <i class="fa-solid fa-globe"></i>
                                            </div>
                                            <a href="#" class="link--portfolio">Lihat Website</a>
                                        </div>
                                    </div>
                                </div>
                                <div class="swiper-slide">
                                    <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                        <div class="content-overlay"></div>
                                        <img src="~/assets/images/twentypicture.png"
                                            class="card-img-top card--image-custom" alt="Twenty Picture">
                                        <div class="card-body">
                                            <h2 class="card-title text-center mb-3">Twenty Picture</h2>
                                        </div>
                                        <div class="content-details">
                                            <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                                <i class="fa-solid fa-globe"></i>
                                            </div>
                                            <a href="#" class="link--portfolio">Lihat Website</a>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="d-none d-lg-block">
                        <div class="row">
                            <div class="col-12 col-lg-3">
                                <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                    <div class="content-overlay"></div>
                                    <img src="~/assets/images/alkopos.png" class="card-img-top card--image-custom"
                                        alt="alkopos">
                                    <div class="card-body">
                                        <h2 class="card-title text-center mb-3">Alko Point of Sales</h2>
                                    </div>
                                    <div class="content-details">
                                        <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                            <i class="fa-solid fa-globe"></i>
                                        </div>
                                        <a href="#" class="link--portfolio">Lihat Website</a>
                                    </div>
                                </div>
                            </div>
                            <div class="col-12 col-lg-3">
                                <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                    <div class="content-overlay"></div>
                                    <img src="~/assets/images/birdnest.png" class="card-img-top card--image-custom"
                                        alt="Birdnest">
                                    <div class="card-body">
                                        <h2 class="card-title text-center mb-3">Bird's Nest Dundee</h2>
                                    </div>
                                    <div class="content-details">
                                        <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                            <i class="fa-solid fa-globe"></i>
                                        </div>
                                        <a href="#" class="link--portfolio">Lihat Website</a>
                                    </div>
                                </div>
                            </div>
                            <div class="col-12 col-lg-3">
                                <div class="card card--custome card--portfolio mb-3 mb-lg-4">
                                    <div class="content-overlay"></div>
                                    <img src="~/assets/images/twentypicture.png" class="card-img-top card--image-custom"
                                        alt="Twenty Picture">
                                    <div class="card-body">
                                        <h2 class="card-title text-center mb-3">Twenty Picture</h2>
                                    </div>
                                    <div class="content-details">
                                        <div class="rounded-circle circle--custome mx-auto mb-3" style="">
                                            <i class="fa-solid fa-globe"></i>
                                        </div>
                                        <a href="#" class="link--portfolio">Lihat Website</a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- End Section Portfolio -->

    <!-- Section Client -->
    <section class="section--client mb--section">
        <div class="container-fluid container-lg">
            <h2 class="section--title text-center">
                Klien <span>Kami</span>
            </h2>
            <!-- Small Devices -->
            <div class="d-block d-lg-none">
                <p class="text-center mb-3 mb-lg-5 px-2 px-lg-0">
                    Kami telah membuat banyak website ataupun desain untuk berbagai perusahaan yang bergerak di bidang
                    ecommerce, UMKM, ekspor, dll.
                </p>
            </div>
            <!-- Large Devices -->
            <div class="d-none d-lg-block">
                <div class="w-50 mx-auto">
                    <p class="text-center mb-3 mb-lg-5">
                        Kami telah membuat banyak website ataupun desain untuk berbagai perusahaan yang bergerak di
                        bidang ecommerce, UMKM, ekspor, dll.
                    </p>
                </div>
            </div>

            <div class="swiper swiper--client mb-0 mb-lg-5">
                <div class="swiper-wrapper">
                    <div class="swiper-slide">
                        <div class="img--client-wrapper">
                            <img src="~/assets/images/client-1.png" class="img-fluid img--client" alt="">
                        </div>
                    </div>
                    <div class="swiper-slide">
                        <div class="img--client-wrapper">
                            <img src="~/assets/images/client-2.png" class="img-fluid img--client" alt="">
                        </div>
                    </div>
                    <div class="swiper-slide">
                        <div class="img--client-wrapper">
                            <img src="~/assets/images/client-3.png" class="img-fluid img--client" alt="">
                        </div>
                    </div>
                    <div class="swiper-slide">
                        <div class="img--client-wrapper">
                            <img src="~/assets/images/client-4.png" class="img-fluid img--client" alt="">
                        </div>
                    </div>
                    <div class="swiper-slide">
                        <div class="img--client-wrapper">
                            <img src="~/assets/images/client-1.png" class="img-fluid img--client" alt="">
                        </div>
                    </div>
                    <div class="swiper-slide">
                        <div class="img--client-wrapper">
                            <img src="~/assets/images/client-2.png" class="img-fluid img--client" alt="">
                        </div>
                    </div>
                    <div class="swiper-slide">
                        <div class="img--client-wrapper">
                            <img src="~/assets/images/client-3.png" class="img-fluid img--client" alt="">
                        </div>
                    </div>
                    <div class="swiper-slide">
                        <div class="img--client-wrapper">
                            <img src="~/assets/images/client-4.png" class="img-fluid img--client" alt="">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- End Section Client -->

    <!-- Section Contact Us -->
    <section class="section--contact-us mb--section">
      <div class="container-fluid container-lg">
        <h2 class="section--title text-center mb-5">
          <span>Kontak</span>
        </h2>
        <div class="row equal">
          <div class="col-12 col-lg-6 mb-4 mb-lg-0">
            <div class="row mb-3">
              <div class="col-1 col-lg-1">
                <p class="text-center icon--contact">
                  <i class="fa-brands fa-whatsapp fa-2xl"></i>
                </p>
              </div>
              <div class="col-11 col-lg-9 ps-4 ps-lg-3">
                <p>
                  +62 425-6563-0874
                </p>
              </div>
            </div>
            <div class="row mb-3">
              <div class="col-1 col-lg-1">
                <p class="text-center icon--contact">
                  <i class="fa-solid fa-envelope fa-2xl"></i>
                </p>
              </div>
              <div class="col-11 col-lg-9 ps-4 ps-lg-3">
                <p>
                  info@semikode.com
                </p>
              </div>
            </div>
            <div class="row mb-3">
              <div class="col-1 col-lg-1">
                <p class="text-center icon--contact">
                  <i class="fa-brands fa-instagram fa-2xl"></i>
                </p>
              </div>
              <div class="col-11 col-lg-9 ps-4 ps-lg-3">
                <p>
                  @semikode
                </p>
              </div>
            </div>
            <div class="row">
              <div class="col-1 col-lg-1">
                <p class="text-center icon--contact">
                  <i class="fa-solid fa-map fa-2xl"></i>
                </p>
              </div>
              <div class="col-11 col-lg-9 ps-4 ps-lg-3">
                <p>
                  Dk. Bandar, Desa Pakijangan, Kec. Bulakamba Kab. Brebes, Jawa Tengah
                </p>
              </div>
            </div>
          </div>
          <div class="col-12 col-lg-6">
            <div class="card--custome form--contact">
              <form action="">
                <div class="form-group mb-4 mb-lg-4">
                  <input type="text" class="input--custome" placeholder="Nama Lengkap">
                </div>
                <div class="form-group mb-4 mb-lg-4">
                  <input type="text" class="input--custome" placeholder="No. Telepon">
                </div>
                <div class="form-group mb-4 mb-lg-4">
                  <input type="text" class="input--custome" placeholder="Email">
                </div>
                <div class="form-group mb-4 mb-lg-4">
                  <input type="text" class="input--custome" placeholder="Message">
                </div>
                <div class="d-flex justify-content-end">
                  <button class="btn btn--crayola">Kirim</button>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- End Section Contact Us -->

    <!-- Section Get Started -->
    <section class="section--getstarted mb-0 mb-lg-5">
      <div class="container-fluid container-lg">
        <div class="container--crayola">
          <div class="d-lg-flex justify-content-lg-between align-items-lg-center">
            <div>
              <h3 class="text-white text-center text-lg-start">
                Butuh Konsultasi Gratis
              </h3>
              <p class="mb-lg-0 text-white text-center text-lg-start">
                Hubungi kami segera
              </p>
            </div>
            <div>
              <button class="btn btn--outline-crayola btn--contant-us btn--no-hover">
                Hubungi Kami&emsp;<i class="fa-solid fa-paper-plane"></i>
              </button>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- End Section Get Started -->

    <Footer />
  </div>
</template>

<script>
  import { Swiper } from 'swiper';
  import 'swiper/swiper-bundle.min.css' 
  export default {
    name: 'SEMIKODE',
    mounted() {
      const swiperService = new Swiper(".swiper--service", {
          slidesPerView: 1.2,
          spaceBetween: 10,
          breakpoints: {
              768: {
                  slidesPerView: 4,
                  spaceBetween: 25,
              },
          },
      });
      const swiperClient = new Swiper(".swiper--client", {
          slidesPerView: 2,
          spaceBetween: 10,
          breakpoints: {
              768: {
                  slidesPerView: 6,
                  spaceBetween: 20,
              },
          },
      });
      const swiperPortfolioWebsite = new Swiper(".swiper--portfolio-website", {
          slidesPerView: 1.2,
          spaceBetween: 10,
      });
    },
    data () {
      return {
        openTab: 1,
      }
    },
    methods: {
      toggleTabs: function(tabNumber){
        this.openTab = tabNumber
        let tablinks = document.getElementsByClassName("tab--link");
        console.log(tablinks);
      }

  //     function openTab(evt, tabName) {
  //   var i, tabcontent, tablinks;
  //   tabcontent = document.getElementsByClassName("tabcontent");
  //   for (i = 0; i < tabcontent.length; i++) {
  //       tabcontent[i].style.display = "none";
  //   }
  //   tablinks = document.getElementsByClassName("tab--link");
  //   for (i = 0; i < tablinks.length; i++) {
  //       tablinks[i].className = tablinks[i].className.replace(" active", "");
  //   }
  //   document.getElementById(tabName).style.display = "block";
  //   evt.currentTarget.className += " active";
  // }
    }
  }
</script>

<style scoped>
  .section--hero {
    background-image: url("~/assets/images/bg-hero.png");
  }
</style>
