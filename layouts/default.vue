<template>
  <v-app>
    <!--<v-navigation-drawer-->
      <!--v-model="drawer"-->
      <!--:mini-variant="miniVariant"-->
      <!--:clipped="clipped"-->
      <!--fixed-->
      <!--app-->
    <!--&gt;-->
      <!--<v-list>-->
        <!--<v-list-item-->
          <!--v-for="(item, i) in items"-->
          <!--:key="i"-->
          <!--:to="item.to"-->
          <!--router-->
          <!--exact-->
        <!--&gt;-->
          <!--<v-list-item-action>-->
            <!--<v-icon>{{ item.icon }}</v-icon>-->
          <!--</v-list-item-action>-->
          <!--<v-list-item-content>-->
            <!--<v-list-item-title v-text="item.title" />-->
          <!--</v-list-item-content>-->
        <!--</v-list-item>-->
      <!--</v-list>-->
    <!--</v-navigation-drawer>-->
    <!--<v-app-bar-->
      <!--:clipped-left="clipped"-->
      <!--fixed-->
      <!--app-->
    <!--&gt;-->
      <!--<v-app-bar-nav-icon @click.stop="drawer = !drawer" />-->
      <!--<v-btn-->
        <!--icon-->
        <!--@click.stop="miniVariant = !miniVariant"-->
      <!--&gt;-->
        <!--<v-icon>mdi-{{ `chevron-${miniVariant ? 'right' : 'left'}` }}</v-icon>-->
      <!--</v-btn>-->
      <!--<v-btn-->
        <!--icon-->
        <!--@click.stop="clipped = !clipped"-->
      <!--&gt;-->
        <!--<v-icon>mdi-application</v-icon>-->
      <!--</v-btn>-->
      <!--<v-btn-->
        <!--icon-->
        <!--@click.stop="fixed = !fixed"-->
      <!--&gt;-->
        <!--<v-icon>mdi-minus</v-icon>-->
      <!--</v-btn>-->
      <!--<v-toolbar-title v-text="title" />-->
      <!--<v-spacer />-->
      <!--<v-btn-->
        <!--icon-->
        <!--@click.stop="rightDrawer = !rightDrawer"-->
      <!--&gt;-->
        <!--<v-icon>mdi-menu</v-icon>-->
      <!--</v-btn>-->
    <!--</v-app-bar>-->
    
    <section class="site-header">
	    <div class="container-fluid">
			    <div class="top-bar d-flex flex-wrap justify-content-between">
				    <div class="flex-grow-1">
					    <button class="btn-custom"> sell on kopit </button>
				    </div>
				    <div class="flex-grow-1 d-flex justify-end">
					    <div class="flex-grow-1 d-flex justify-end align-center">
						    <input type="search" class="search-btn" placeholder="search">
						    <i class="mdi mdi-cart-outline"></i>
						    <i class="mdi mdi-account-outline"></i>
					    </div>
				    </div>
			    </div>
			    <div class="nav-container">
			        <div class="container">
				        <div class="nav">
					        <div class="brand">
						        <img src="../assets/images/logo.png"/>
					        </div>
					        <div class="items">
						        <ul>
							        <li> <a href="" class="active"> women </a> </li>
							        <li> <a href=""> men </a> </li>
							        <li> <a href=""> home & garden</a> </li>
							        <li> <a href=""> health & beauty </a> </li>
							        <li> <a href=""> collectibilities & art  </a> </li>
							        <li> <a href="">hand bags </a> </li>
							        <li> <a href=""> jewellery </a> </li>
							        <li> <a href=""> <i class="mdi mdi-apple-keyboard-command"></i>  </a> </li>
						        </ul>
					        </div>
				        </div>
				        <div class="breadcrumb">
					        <ul>
						        <li><a href="">Home</a></li>
						        <li><a href="">Fashion</a></li>
						        <li><a href="">woman Shoes</a></li>
					        </ul>
				        </div>
			        </div>
			    </div>
	    </div>
    </section>
    
    <v-content>
      <v-container>
        <nuxt />
      </v-container>
    </v-content>
    
    <!--<v-navigation-drawer-->
      <!--v-model="rightDrawer"-->
      <!--:right="right"-->
      <!--temporary-->
      <!--fixed-->
    <!--&gt;-->
      <!--<v-list>-->
        <!--<v-list-item @click.native="right = !right">-->
          <!--<v-list-item-action>-->
            <!--<v-icon light>-->
              <!--mdi-repeat-->
            <!--</v-icon>-->
          <!--</v-list-item-action>-->
          <!--<v-list-item-title>Switch drawer (click me)</v-list-item-title>-->
        <!--</v-list-item>-->
      <!--</v-list>-->
    <!--</v-navigation-drawer>-->
    
  <section class="footer">
	<div class="container">
		<v-row >
			<v-col cols="3" sm="12"  md="3" >
				<h3 >Links</h3>
				<ul>
					<li> <a href=""> About </a> </li>
					<li> <a href=""> Affiliates </a> </li>
					<li> <a href=""> Contact </a> </li>
					<li> <a href=""> Privacy Policy </a> </li>
					<li> <a href=""> Terms of use </a> </li>
				</ul>
			</v-col>
			<v-col cols="3" sm="12"  md="3" >
				<h3>newsletter</h3>
			
				 <p class="pt-2 subscribe" >
					 subscribe to our newsletter, so that you can be the first to know about new offers and promotions.
				 </p>
				<label class="newsletter">
					<input type="text" placeholder="Enter email Address">
					<button class="btn-custom">
					    <i class="mdi mdi mdi-arrow-right"></i>
			     	</button>
				</label>
			</v-col>
			<v-col cols="4" sm="12"  md="4" >
				<h3>instagram feeds</h3>
				<p class="pt-1">
					<img src="../assets/images/feed.JPG" class="feed">
					<img src="../assets/images/feed.JPG" class="feed">
					<img src="../assets/images/feed.JPG" class="feed">
					<img src="../assets/images/feed.JPG" class="feed">
					<img src="../assets/images/feed.JPG" class="feed">
					<img src="../assets/images/feed.JPG" class="feed">
					<img src="../assets/images/feed.JPG" class="feed">
					<img src="../assets/images/feed.JPG" class="feed">
				</p>
			</v-col>
			<v-col cols="2" sm="12"  md="2" >
				<h3>Follow us </h3>
				<p>Let us be social</p>
				<ul class="social">
					<li>
						<a href="" title="Facebook"> <img src="../assets/images/fb.JPG" > </a>
					</li>
					<li>
						<a href="" title="Twitter"> <img src="../assets/images/tw.JPG" > </a>
					</li>
					<li>
						<a href="" title="Google Plus"> <img src="../assets/images/g.JPG" > </a>
					</li>
				</ul>
			</v-col>
		</v-row>
	</div>
  </section>
  </v-app>
</template>

<script>
export default {
  data () {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      items: [
        {
          icon: 'mdi-apps',
          title: 'Welcome',
          to: '/'
        },
        {
          icon: 'mdi-chart-bubble',
          title: 'Inspire',
          to: '/inspire'
        }
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: 'Vuetify.js'
    }
  }
}
</script>
