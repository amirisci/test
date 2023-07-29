<template >

  <v-app >
    <div>
      <!--toolbar header-->
    <v-toolbar flat app
    height="80px"
      color="#FFF9C4"
      image="https://cdn.vuetifyjs.com/images/backgrounds/vbanner.jpg"
    >
          <v-app-bar-nav-icon @click.stop="drawer= !drawer"></v-app-bar-nav-icon>
        
        <v-navigation-drawer
        app
        color="black"
        v-model="drawer"
        class="indigo"
        temporary
      ></v-navigation-drawer>
        <v-spacer></v-spacer>
  <div class=" d-flex justify-space-around text-center">
    <v-menu
    anchor="bottom-end"
      open-on-hover
    >
      <template v-slot:activator="{ props }">
        <v-btn
           flat
           class=" brown black--text"
           v-bind="props">
           shit
        </v-btn>
      </template>
      <v-list>
        <v-list-item>
          <v-list-item-title>hhhh
          </v-list-item-title>jjjjjj
        </v-list-item>
      </v-list>
    </v-menu>
      <!-- <v-btn
      class="white black--text"
    >
      damn

      <v-menu  activator="parent">
        <v-list>
          <v-list-item>
           <span>hallo</span>
          </v-list-item>
          <v-list-item>
           <span>hallo</span>
          </v-list-item>
        </v-list>
      </v-menu>
    </v-btn> -->
  </div>
  
    
      
       <div class="logo">
        
        <FanavaranLogo/>
      </div>
      
    </v-toolbar>
  </div>
     <!-- end of the header-->
   
<!--carousel image-->
    <v-carousel
    cycle
    height="600"
    hide-delimiter-background
    show-arrows="hover"
  >
    <v-carousel-item>
      <img src="http://parscognition.ir/wp-content/uploads/2022/02/Untitled5.jpg" alt="" title="" style="width: 100%; height: 100%; margin-top: 0px; margin-left: 0px;">

    </v-carousel-item>
    <v-carousel-item>
      <img src="http://parscognition.ir/wp-content/uploads/2022/02/Untitled10-1280x530.jpg" alt="" title="" style="height: 100%; width: 100%; margin-top: 0px; margin-left: 0px;">
    </v-carousel-item>
  </v-carousel>
  <!--end of carousel image-->


    <v-row class="about-us">
    <br>
      <div >
        <h3 align="center">about us</h3>
        <p  class="text-center"  padding-left="10px"> Lorem, ipsum dolor sit amet consectetur adipisicing elit. Delectus officiis nemo aliquid dolorem omnis et eum magnam laudantium quos. Alias reiciendis quia totam sapiente quasi. Non quas sapiente eveniet voluptas!
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Saepe sint aperiam omnis expedita exercitationem voluptatem, commodi rem pariatur, dolore repellendus suscipit. Modi, alias. Distinctio non assumenda laboriosam officia repudiandae esse!
        </p>
      </div>
      
    </v-row>

    <v-row class="about-us" >


      <div  class="boo">
        <h3 align="center">products</h3>
        <br><br>
          <v-row>
            <v-col col="2" offset="2" >
              <v-card 
              width="120"
              flat
              color="#FFECB3">
                <v-btn id="bab"
                depressed boredr
            class="pa-10  rounded-circle"
                color="brown" 
                border="red">
                <v-icon x-large> mdi-hospital-building </v-icon>
                 </v-btn>
                 <p class="black--text text-center">
    hospital
                 </p>
              </v-card>
           
     </v-col>
             <v-col col="2" offset="3" >
              <v-btn
                class="pa-7 rounded-circle"
                color="brown">
                <svg-icon type="mdi" :path="path"></svg-icon>
                
              </v-btn>
              
             </v-col>
         </v-row>
         <br><br><br>
         <v-row>
              <v-col col="2" offset="2" >
                <v-btn
                class="pa-7 rounded-circle"
                color="brown">
                <v-icon x-large> mdi-school-building </v-icon>
                
             </v-btn>
              </v-col>
              <v-col col="2" offset="3" >
                <v-btn
                class="pa-7 rounded-circle"
                color="brown">
                <v-icon x-large> mdi-medicine </v-icon>
             </v-btn>
             
              </v-col>
            
         </v-row>
     </div>
     
    </v-row>
      <!--news-->
      <div class="boo" id="colorr" >
        <!-- <v-row  class="about-us" id="color" background-color="#FFECB3"> -->
        <div >
          <p color="black" class="text-center">news</p>
        </div>
         
      
    <v-row ><v-col col="6" >
          <v-card
  class="mx-auto"
  max-width="400"
  color="#FFECB3"
>
  <v-img
    class="align-end text-white"
    width="410" height="298"
    src="http://parscognition.ir/wp-content/uploads/2022/01/Image-219-e1643192856690-410x298.jpg"
    cover
  >
    
  </v-img>

  <v-card-subtitle class="black--text">
    Lorem ipsum dolor sit amet.
  </v-card-subtitle>

  <v-card-text class="black--text">

     Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nulla tempora aut sunt numquam repellat exercitationem quod, magni voluptatibus, qui mollitia quos. Qui praesentium recusandae laboriosam magnam odit iure perferendis nisi.
  </v-card-text>

  
</v-card>
      </v-col>
      <v-col col="6" >
        
        <v-card
  class="mx-auto"
  max-width="400"
  color="#FFECB3"
>
  <v-img
    class="align-end text-white"
    width="410" height="298"
    src="http://parscognition.ir/wp-content/uploads/2022/01/Image-219-e1643192856690-410x298.jpg"
    cover
  >
    
  </v-img>

  <v-card-subtitle  class="black--text">
    Lorem ipsum dolor sit amet.
  </v-card-subtitle>

  <v-card-text  class="black--text">

    Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nulla tempora aut sunt numquam repellat exercitationem quod, magni voluptatibus, qui mollitia quos. Qui praesentium recusandae laboriosam magnam odit iure perferendis nisi.
  </v-card-text>

  
</v-card>
      </v-col></v-row>
        
      
      
    <!-- </v-row> -->
      </div>
      
      <!--coaperators-->
      <v-card backgrounds=""></v-card>
<br><br><br><br>
    <!--footer-->
    <v-footer style="
    background-image : url(&quot;http://parscognition.ir/wp-content/uploads/2015/03/vector-yellow-abstract-background.jpg&quot;)
    "
    color="#FFF9C4"
    class="footer-index"
      :absolute="!fixed"
      app
    > 
      <!-- <v-col col="6" offset="1"><span class="footer">footer</span></v-col>
      <v-spacer></v-spacer>
      <v-col col="6" offset="2"><FanavaranLogo/></v-col> -->
      <h1>footer</h1>
      <v-spacer></v-spacer>

      <div class="logo">
        <FanavaranLogo/>
      </div>
      
        
    
    </v-footer >
    
  </v-app>
</template>
<script>

// import SvgIcon from '@jamescoyle/vue-icon';
import { mdiHospitalBuilding } from '@mdi/js';

import FanavaranLogo from "~/components/FanavaranLogo.vue";
export default ({
  components:{
    FanavaranLogo
  },
  data: () => ({
    drawer:false,
    }),
    items: [
        { title: 'Click Me' },
        { title: 'Click Me' },
        { title: 'Click Me' },
        { title: 'Click Me 2' },
      ],
    name: 'App',
  //   name: "my-component",
  // components: {
  //   SvgIcon
  // },
  // data() {
  //   return {
  //      path: mdiHospitalBuilding,
  //   }
  // }
    
 
  
})





</script>

<style>

  .footer-index{
    height: auto;
  
  }

  .logo{
      display: flex; 
       }
  .fanavaran-logo{
    height: 80px;
    justify-items: end;}


  .footer{
    color:black;
  }
  .about-us{
    height: 600px;
    background-color:#FFECB3 ;
    color: black;
  }
  .boo{
    background-color:FFECB3;
    width: 100%;
    height: max-content;
  }
 .cardss{
  background-color: #FFECB3;
  color: black;
 }
 .txt{
  color: black;
 }
 #color{
  background-color: #FFECB3;
  color: black;
 }
 #colorr{
  background-color:#FFECB3;
  color: black;
 }

 
</style>
