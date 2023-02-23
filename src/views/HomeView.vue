<template>
  <v-app :style="{background: $vuetify.theme.themes.dark.background}"></v-app>
  <NavBar />
  <v-container fluid>
    <v-row>
      <v-col cols="6">
        <v-img src="DSC_9800.jpg" contain max-height="300">
        </v-img>
      </v-col>
      <v-col cols="6">
        <h5 class="red--text text-darken-4 top">Hello I'm Isaac</h5>
        <h1 class="white--text">Viussl Designer</h1>
        <p class="grey--text">Lorem ipsum dolor sit, amet consectetur adipisicing elit. 
          Ipsa sit ullam aliquid, natus minus recusandae totam assumenda 
          deserunt culpa dignissimos, inventore nisi dicta sunt
           modi explicabo harum porro at? Animi?</p>
           <v-btn title color="#A71210" dark>about me</v-btn>
      </v-col>
      <v-col cols="12" class="padd">
         <div class="first" id="project">
          <v-row>
            <v-col cols="12">
              <div class="child bgColor1">
                <v-icon color="#A7121D" x-large class="ml-3">
                  mdi-palette-switch
                </v-icon>
                <h3 class="white--text ml-3mt-4">UI Design</h3>
                <p class="grey--text ml-3 mt-6">Lorem, ipsum dolor
                   sit amet <br />consstur asdu</p>
                   <v-btn color="#A7121D" dark text>
                    know more
                    <v-icon right>md1-arrow-right</v-icon>
                   </v-btn>
              </div>
              <div class="child bgColor2">
                <v-icon x-large class="ml-3" dark>md1-shopping
                </v-icon>
                <h3 class="white--text ml-3 mt-4">Product Design</h3>
                <p class="grey--text ml-3 mt-6">
                  Lorem,ipsu dolor slt amet <br />consect adiepe
                </p>
                <v-btn dark text>
                  know more
                  <v-icon right>
                    mdi-arrow-right</v-icon></v-btn>
              </div>
              <div class="child bgColor1">
                <v-icon color="#A71210" x-large class="ml-3">mdi-book-open-page-variant</v-icon>
                <h3 class="white--text ml-3 mt-4">Baranding</h3>
                <p class="grey--text ml-3 mt-6"> Lorem, ipsum color elt<br />rrgrg ghg</p>
                <v-btn color="#A7121D" dark text>
                    know more
                    <v-icon right>md1-arrow-right</v-icon>
                   </v-btn> 
              </div>
            </v-col>
            <v-col cols="12" class="mt-10">
              <div class="child">
                <h1 class="red--text text-darken-4 mt-4 number">12</h1>
                <h3 class="white--text mt-4">Years Experience</h3>
              </div>
              <div class="child2 mRight">
                <v-row>
                  <v-col cols="12" class="childcol">
                    <div class="child2 mButton padding bgColor1">
                      <h1 class="red--text text--darken-4">60+</h1>
                      <p class="grey--text">Client</p>
                    </div>
                  </v-col>
                  <v-col cols="12" class="childcol">
                    <div class="child2 padding bgColor1">
                      <h1 class="red--text text--darken-4">12+</h1>
                      <p class="grey--text">Completed Project</p>
                    </div>
                  </v-col>
                </v-row>
              </div>

              <div class="child2">
                <v-row>
                  <v-col cols="12" class="childcol">
                    <div class="child2 mButton padding bgColor1">
                      <h1 class="red--text text--darken-4">00</h1>
                      <p class="grey--text">Years Experience</p>
                    </div>
                  </v-col>
                  <v-col cols="12" class="childcol">
                    <div class="child2 padding bgColor1">
                      <h1 class="red--text text--darken-4">10</h1>
                      <p class="grey--text">Achievement</p>
                    </div>
                  </v-col>
                </v-row>
              </div>
            </v-col>
          </v-row>
         </div>
      </v-col>

      <v-col md="3" offset-md="3" id="about">
        <h4 class="white--text">Featured Project</h4>
        <p class="grey--text">Lorem ipsum dolor Lorem ipsum dolor</p>
      </v-col>
      <v-col md="3" class="text-end">
        <v-btn tile color="#A7121D" dark>View All</v-btn>
      </v-col>
      <v-col md="3" oofset-md="3">
        <v-card class="pa-2 py-12" outlines title height="250px" color="#1e1e1e">
          <v-img src="DSC_9810" contain></v-img>
        </v-card>
      </v-col>

      <v-col md="3">
        <v-card class="pa-2 py-12" outlines title height="250px" color="#1e1e1e">
          <v-img src="DSC_9810" contain></v-img>
        </v-card>
      </v-col>

      <v-col md="3" offset-md="3">
        <v-btn color="white" dark text class="ml-m4">The Vintage</v-btn><br />
        <v-btn color="#A7121D" dark text class="ml-n4">Know more</v-btn>
        <v-icon right>mdi-arrow-right</v-icon>
      </v-col>
    </v-row>
  </v-container>
</template>
 
<script lang="ts">
import { defineComponent } from 'vue';

// Components
import NavBar from '../components/NavBar.vue';

export default defineComponent({
  name: 'HomeView', 
  components: {
    NavBar,
  },
});
</script>

<style scoped>
.top{
  margin-top:180px;
}
.topInverse{
  margin-top :-250px;
}

.topTolbar{
  margin-top:100px;
  text-align:center;
}

.first{
  width:100%;
  height:610px;
}


.second {
  width: 100%;
  height: 400px;
  background: #181818;
  text-align: center;
  padding: 2rem 2rem;
}

.secondchild1 {
  display: inline-block;
  background-color:#1e1e1e;
  padding:1rem;
  vertical-align :middle;
  margin-top:250px;
}

.child{
  display: inline-block;
  padding:2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-right:8px;
}

.bgColor1{
  background-color: #1e1e1e;
}
.bgColor2{
  background-color: #ce1d2a;
}
.child1{
  display:inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  margin-right:5px;
  width:240px;
}

.child2{
  display: inline-block;
  width: 245px;
  vertical-align: middle;
}

.mRight {
  margin-right:8px;
}

.mButton{
  margin-bottom: 8px;
}
.padding{
  padding: 8px 0px
}

.col-12.padd {
  padding: 12px 0 !important;
}
.col-12.childcol {
  padding: 0 !important;
}

h1.number {
  font-size:50px;
  font-weight: bold;
}
</style>
