<template>
  <div>
    <div class="banner container-fluid position-relative">
      <!-- 背景 -->
      <div class="row container-fluid">
        <div class="col-12 col-xl-8 col-xxl-7 bannerBg position-absolute no-p15">
          <div class="bannerOpacity"></div>
        </div>
      </div>
      <!-- 文字 -->
      <div class="container">
        <div class="col-12 col-xl-4 no-p15 intro" data-aos="fade-right" data-aos-delay="800">
          <h2 class="enIntro marker mb-3">Bar Night,<br>elegant night.</h2>
          <h2 class="chIntro noto bold mb-2">調酒、美食、寧靜之夜</h2>
          <h2 class="chIntro noto bold">在喧囂的塵世裡沉澱心情</h2>
        </div>
      </div>
    </div>
    <div class="white-texture">
      <div class="container pt-5 pb-5 overflow-hidden">
        <div class="row">
          <div class="col-12">
            <intro-swiper></intro-swiper>
          </div>
        </div>
      </div>
    </div>
    <main class="container overflow-hidden py-5">
      <div class="row d-flex justify-content-lg-center">
        <div class="col-12 col-lg-12 d-md-flex flex-md-wrap justify-content-md-between">
          <div class="card border-0 mb-4 flex-lg-row">
            <img
              src="https://hexschool-api.s3.us-west-2.amazonaws.com/custom/oxZvIQttAssTicPrF0XTqYZJKHu49WRjoUL90Ug7pNlujSGgmkR3arWQyG52luBYCORQAj4GG0hBleHMq6E45dZXPhY3Vfrb7kkVS9j7encqsfog0pWRYqTKXmnSd7Ny.jpg"
              class="clippy-reverse card-img-top position-60 trans" data-aos="fade-right" data-aos-offset="400"
              data-aos-once="true" alt="餐點皆可客製化">
            <div class="card-body p-lg-3 d-lg-flex justify-content-lg-center align-items-lg-center">
              <h3 class="card-text text-white bold noto">專業調酒師為您調製多樣化的調酒，口感從酸到甜、酒感從輕到重，都可為您量身調製。
                <router-link to="/products" class="mt-3 mt-md-4 text-main noto d-block h5">查看更多 &#8594;
                </router-link>
              </h3>
            </div>
          </div>
          <div class="card border-0 mb-4 flex-lg-row-reverse">
            <img src="https://hexschool-api.s3.us-west-2.amazonaws.com/custom/cgJOrATGPksVt37iK6MBBIyOUB4eYHhIXr8iwK2QE6EbiOgCpI063GLQYs7gKGGG1ubzMYnMMlj971IaGJPt8D75uFFNPAMbWjZk62oxEYx5ZTVeHNtphactObddeJVz.jpg" class="clippy card-img-top position-74 trans" data-aos="fade-left"
              data-aos-offset="400" data-aos-once="true" alt="每日採買新鮮材料">
            <div class="card-body p-lg-3 d-lg-flex justify-content-lg-center align-items-lg-center">
              <h3 class="card-text text-white bold noto">每日採買新鮮食材及調酒原料，六大基酒皆選用知名品牌，水果、花香、茶香、蜜餞等原料皆為手工調製。
                <router-link to="/products" class="mt-3 mt-md-4 text-main noto d-block h5">查看更多 &#8594;
                </router-link>
              </h3>
            </div>
          </div>
          <div class="card border-0 mb-4 flex-lg-row">
            <img src="https://hexschool-api.s3.us-west-2.amazonaws.com/custom/owJoCqmbTCMroqpujv5GZTDLIfR6pC5hlo03usUo1B3hMNLT9XbLOEy2eVDOeoxW2uPgBcfBL67c835znpWCCLec0k1T5l4gzMvVCcmLff56Z3twqMeh3oWv4xbJoRt7.jpg" class="clippy-reverse card-img-top position-90 trans"
              data-aos="fade-right" data-aos-offset="400" data-aos-once="true" alt="店內用水皆使用除下淨水系統">
            <div class="card-body p-lg-3 d-lg-flex justify-content-lg-center align-items-lg-center">
              <h3 class="card-text text-white bold noto">調酒最重要的元素就是水。全店使用 3M
                廚下淨水系統，從飲用水到冰塊皆純淨無瑕，同時保留水中的微量元素。
                <router-link to="/products" class="mt-3 mt-md-4 text-main noto d-block h5">查看更多 &#8594;
                </router-link>
              </h3>
            </div>
          </div>
          <div class="card border-0 flex-lg-row-reverse">
            <img src="https://hexschool-api.s3.us-west-2.amazonaws.com/custom/tyq0uNhjefcUfCQYteIOawfgLiS7AzUuxlZKXcrWf7ZknXvJC2KnhVZg4QjBsozUT7TzkuLGHCs1YxMhTIQ4KAB12cPPm2Fjx1AjFbbxmcGpTxRSi5rB7Vlm5s3n1BFN.jpg" class="clippy card-img-top trans" data-aos="fade-left"
              data-aos-offset="400" data-aos-once="true" alt="最頂尖的食材搭配最頂尖的手藝">
            <div class="card-body p-lg-3 d-lg-flex justify-content-lg-center align-items-lg-center">
              <h3 class="card-text text-white bold noto">每日採買最新鮮最頂級的食材，配上本店主廚最頂尖的手藝，讓您品飲的同時也能填飽肚子。
                <router-link to="/products" class="mt-3 mt-md-4 text-main noto d-block h5">查看更多 &#8594;
                </router-link>
              </h3>
            </div>
          </div>
        </div>
      </div>
    </main>
    <div class="white-texture overflow-hidden py-5">
      <div class="container">
        <div class="row">
          <div class="col-12">
            <ProductSwiper></ProductSwiper>
          </div>
        </div>
      </div>
    </div>
    <div class="info container black-texture">
      <div class="row justify-content-center">
        <div class="col-12 col-sm-8 col-lg-6 py-5 mb-3 mb-sm-0">
          <div class="infoText py-lg-5 bg-dark">
            <h3 class="text-main marker text-center mb-2 mb-lg-4">bar night <span class="noto">夜吧</span>
            </h3>
            <ul class="list-unstyled">
              <li class="text-center text-main bold mb-2">TEL</li>
              <li class="text-center text-white h5 pb-3 mb-3 border-bottom">(02)2111-0451</li>
              <li class="text-center text-main bold mb-2">ADDRESS</li>
              <li class="text-center text-white h5 pb-3 mb-3 border-bottom">台北市中正區重慶南路一段122號</li>
              <li class="text-center text-main bold mb-2">OPEN TIME</li>
              <li class="text-center text-white h5">週二至週四：19:00-24:00</li>
              <li class="text-center text-white h5 pb-3 mb-3 border-bottom">週五至週日：18:00-01:00</li>
            </ul>
            <ul class="d-flex justify-content-center list-unstyled mb-0 h4">
              <li><a href="#" class="text-white mx-3"><i class="fab fa-facebook"></i></a></li>
              <li><a href="#" class="text-white mx-3"><i class="fab fa-instagram"></i></a></li>
              <li><a href="#" class="text-white ml-3"><i class="fab fa-line"></i></a></li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
