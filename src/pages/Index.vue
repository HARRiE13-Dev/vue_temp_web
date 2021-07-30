<template>
  <div>
    <div class="page-header clear-filter" filter-color="blue">
      <parallax
        class="page-header-image"
        style="background-image:url('img/header.jpg')"
      >
      </parallax>
      <div class="container ">

       <div class="row justify-content-center card">
        <div class="col-12">
          <el-carousel height="500px">

            <el-carousel-item>
              <img class="d-block" src="img/bg1.jpg" alt="First slide" />
              <div class="carousel-caption d-none d-md-block">
                <h5>Nature, United States</h5>
              </div>
            </el-carousel-item>

            <el-carousel-item>
              <img class="d-block" src="img/bg3.jpg" alt="Second slide" />
              <div class="carousel-caption d-none d-md-block">
                <h5>Somewhere Beyond, United States</h5>
              </div>
            </el-carousel-item>


          </el-carousel>
        </div>
      </div>
      
        
     
        <!-- Footer Page -->
        <h6 class="category category-absolute">
          Computer Science Divition, Faculty of Scicence, Maejo University
        </h6>
        
      </div>
    </div>
    
   
      <div class="main">
      <div class="section section-images">
        <div class="container">
          <div class="row">
            <div class="col-md-12">
              <div class="hero-images-container">
                <img src="img/micon.png" alt="" />
              </div>
              
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="card-deck">
  <div class="card">
    <img class="card-img-top" src="img/micon.png" alt="Card image cap">
    <div class="card-body">
      <h5 class="card-title">Card title</h5>
      <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
      <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
    </div>
  </div>
  <div class="card">
    <img class="card-img-top" src="img/micon.png" alt="Card image cap">
    <div class="card-body">
      <h5 class="card-title">Card title</h5>
      <p class="card-text">This card has supporting text below as a natural lead-in to additional content.</p>
      <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
    </div>
  </div>
  <div class="card">
    <img class="card-img-top" src="img/micon.png" alt="Card image cap">
    <div class="card-body">
      <h5 class="card-title">Card title</h5>
      <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
      <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
    </div>
  </div>
</div>

 



   
  
  </div>
</template>
<script>
import { Carousel, CarouselItem } from 'element-ui';


export default {
  name: 'index',
  bodyClass: 'index-page',
  components: {
     [Carousel.name]: Carousel,
    [CarouselItem.name]: CarouselItem
  }
};
</script>
<style></style>
