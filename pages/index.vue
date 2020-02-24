<template>
  <section class="products-section">
    <v-row class="mobile-view">
      <v-col cols="3" sm="12"  md="3"  class="sidebar">
        <v-card class=" sidebar-items">
          <div class="header">
            categories
          </div>
          <div class="content">
            <ul>
              <li><a href="">Clothing <span>(314)</span></a></li>
              <li><a href="" class="active">Shoes <span>(314)</span></a></li>
              <li><a href="">Accessories <span>(314)</span></a></li>
              <li><a href="">Vintage <span>(314)</span></a></li>
              <li><a href="">Formal & Wedding <span>(314)</span></a></li>
            </ul>
          </div>
        </v-card>
        <v-card class=" sidebar-items" >
          <div class="header">
            color
          </div>
          <div class="content">
            <ul>
              <li><a href="">black <span>(314)</span></a></li>
              <li><a href="" class="active">beige <span>(314)</span></a></li>
              <li><a href="">silver <span>(314)</span></a></li>
              <li><a href="">ivory <span>(314)</span></a></li>
            </ul>
          </div>
        </v-card>
        <v-card class=" sidebar-items" >
          <div class="header">
            us size
          </div>
          <div class="content">
            <ul>
              <li>
                <label class="hidden-box">
                  <input type="checkbox" >
                  <div>6 <span>(44)</span>  </div>
                </label>
              </li>
              <li>
                <label class="hidden-box">
                  <input type="checkbox" >
                  <div>6 <span>(44)</span>  </div>
                </label>
              </li>
              <li>
                <label class="hidden-box">
                  <input type="checkbox" >
                  <div>6 <span>(44)</span>  </div>
                </label>
              </li>
              <li>
                <label class="hidden-box">
                  <input type="checkbox" >
                  <div>6 <span>(44)</span>  </div>
                </label>
              </li>
            
            </ul>
          </div>
        </v-card>
        <v-card class=" sidebar-items" >
          <div class="header">
            style
          </div>
          <div class="content">
            <ul>
              <li>
                <label class="hidden-box">
                  <input type="checkbox">
                  <div>6 <span>(44)</span>  </div>
                </label>
              
              </li>
            
            </ul>
          </div>
        </v-card>
        <v-card class=" sidebar-items" >
          <div class="header">
            brands
          </div>
          <div class="content">
            <ul>
              <li>
                <label class="hidden-box">
                  <input type="checkbox">
                  <div>6 <span>(44)</span>  </div>
                </label>
              
              </li>
            
            </ul>
          </div>
        </v-card>
      </v-col>
      <v-col cols="9" md="9" sm="12" xs="12" class="content">
        <v-card class="sort-bar" >
          <div class="left">
            <select name="sort" id="">
              <option value="">default sort </option>
              <option value="">option one </option>
              <option value="">option two </option>
              <option value="">option three </option>
              <option value="">option four </option>
            </select>
          </div>
          <div class="right">
            <ul>
              <li><a href="" ><i class="mdi mdi-arrow-left"></i></a></li>
              <li><a href="" class="active">1</a></li>
              <li><a href="">2</a></li>
              <li><a href="">3</a></li>
              <li><a href="">.</a></li>
              <li><a href="">.</a></li>
              <li><a href="">.</a></li>
              <li><a href="">6</a></li>
              <li><a href=""><i class="mdi mdi-arrow-right"></i></a></li>
            </ul>
          </div>
        </v-card>
        <v-row class="products">
          <v-col cols="4" sm="12" class="product-items" md="4">
            <v-card class="items">
              <img src="../assets/images/1.JPG" alt="">
              <p class="name">Product name here </p>
              <p class="price">$32.00 <span><s>$50.00</s></span></p>
              <div class="bottom-section">
                <div class="review">
                  <i class="mdi mdi-star"></i> <span>4.7</span>
                </div>
                <div class="action">
                  <i class="mdi mdi-cart-outline mr-1"></i>
                  <button class="btn-custom">buy</button>
                </div>
              </div>
            </v-card>
          </v-col>
          <v-col cols="4" sm="12" class="product-items" md="4">
            <v-card class="items">
              <img src="../assets/images/2.JPG" alt="">
              <p class="name">Product name here </p>
              <p class="price">$32.00 <span><s>$50.00</s></span></p>
              <div class="bottom-section">
                <div class="review">
                  <i class="mdi mdi-star"></i> <span>4.7</span>
                </div>
                <div class="action">
                  <i class="mdi mdi-cart-outline mr-1"></i>
                  <button class="btn-custom">buy</button>
                </div>
              </div>
            </v-card>
          </v-col>
          <v-col cols="4" sm="12" class="product-items" md="4">
            <v-card class="items">
              <img src="../assets/images/3.JPG" alt="">
              <p class="name">Product name here </p>
              <p class="price">$32.00 <span><s>$50.00</s></span></p>
              <div class="bottom-section">
                <div class="review">
                  <i class="mdi mdi-star"></i> <span>4.7</span>
                </div>
                <div class="action">
                  <i class="mdi mdi-cart-outline mr-1"></i>
                  <button class="btn-custom">buy</button>
                </div>
              </div>
            </v-card>
          </v-col>
          <v-col cols="4" sm="12" class="product-items" md="4">
            <v-card class="items">
              <img src="../assets/images/1.JPG" alt="">
              <p class="name">Product name here </p>
              <p class="price">$32.00 <span><s>$50.00</s></span></p>
              <div class="bottom-section">
                <div class="review">
                  <i class="mdi mdi-star"></i> <span>4.7</span>
                </div>
                <div class="action">
                  <i class="mdi mdi-cart-outline mr-1"></i>
                  <button class="btn-custom">buy</button>
                </div>
              </div>
            </v-card>
          </v-col>
          <v-col cols="4" sm="12" class="product-items" md="4">
            <v-card class="items">
              <img src="../assets/images/2.JPG" alt="">
              <p class="name">Product name here </p>
              <p class="price">$32.00 <span><s>$50.00</s></span></p>
              <div class="bottom-section">
                <div class="review">
                  <i class="mdi mdi-star"></i> <span>4.7</span>
                </div>
                <div class="action">
                  <i class="mdi mdi-cart-outline mr-1"></i>
                  <button class="btn-custom">buy</button>
                </div>
              </div>
            </v-card>
          </v-col>
          <v-col cols="4" sm="12" class="product-items" md="4">
            <v-card class="items">
              <img src="../assets/images/3.JPG" alt="">
              <p class="name">Product name here </p>
              <p class="price">$32.00 <span><s>$50.00</s></span></p>
              <div class="bottom-section">
                <div class="review">
                  <i class="mdi mdi-star"></i> <span>4.7</span>
                </div>
                <div class="action">
                  <i class="mdi mdi-cart-outline mr-1"></i>
                  <button class="btn-custom">buy</button>
                </div>
              </div>
            </v-card>
          </v-col>
        </v-row>
      </v-col>
    </v-row>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  components: {
    Logo,
    VuetifyLogo
  }
}
</script>
