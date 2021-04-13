<template>
    <div>
        <div class="nav" ref="set21" v-if="act">
            <div class="nav1" ref="set22">
                <font-awesome-icon class="icon" :icon="['fas', 'sliders-h']" @click="showNav" />
                <div class="nav2">
                <nuxt-link class="link" to="/"><h2>HOME</h2></nuxt-link>
                <nuxt-link class="link" to="about"><h2>ABOUT COMPANY</h2></nuxt-link>
                <nuxt-link class="link" to="team"><h2>OUR TEAM</h2></nuxt-link>
                <nuxt-link class="link" to="production"><h2>PRODUCTION</h2></nuxt-link>
                <nuxt-link class="link" to="products"><h2>PRODUCTS</h2></nuxt-link>
                </div>
                
            </div>
        </div>
    <div class="index">
      <div class="index0">
        <div>
          <font-awesome-icon class="icon2" :icon="['fas', 'sliders-h']" @click="showNav" />
        </div>
        <div class="index1">
          <h2>Sunny</h2>
        </div>
      </div>
     
      
     
    </div>
    <div class="et">
        <div class="et1">
            <h2>SUNNY TEAM</h2>
            <p>Our company's human resources policies are primarily aimed at personal 
                and professional development and are based upon the principles of openness, 
                development, and growth.</p>
            <p>Professionalism and teamwork are our main advantages since these qualities 
                enable us to be efficient and create effective cooperation mechanisms when it 
                comes to our partners.</p>
        </div>
        <div class="et2">
            <div class="et3">
                <img src="/img/mi.jpg" alt="">
                <div class="et5">
                    <p><span class="et4">Pablo Yemets</span></p>
                    <p>Director</p>
                </div>
                
            </div>
            <div class="et3">
                <img src="/img/pe.jpg" alt="">
                <div class="et5">
                    <p><span class="et4">Alina Overko</span></p>
                    <p>Export Manager</p>
                </div>
            </div>
            <div class="et3">
                <img src="/img/fo.jpg" alt="">
                <div class="et5">
                    <p><span class="et4">Anatolii Ryshkin</span></p>
                    <p>Export Manager</p>
                </div>
            </div>
        </div>
        <div class="et6">
            <div>
                <img src="/img/iv.jpg" alt="">
                <div class="et5">
                    <p><span class="et4">Nataliya Kopteva</span></p>
                    <p> Manager</p>
                </div>
            </div>
            <div>
                <img src="/img/lu.jpg" alt="">
                <div class="et5">
                    <p><span class="et4">Alexey Andriyash</span></p>
                    <p>Head of Retail Department</p>
                </div>
            </div>
        </div>
    </div>
    <back-to-top />
    <footer-section/>
    </div>
</template>

<style scoped>
    .nav{
        width: 30%;
        height: 100vh;
        position: fixed;
        top: 0;
        left: 0;
        background: #ffbe3c;
    }
    .nav1{
        margin-left: 3rem;
        margin-right: 3rem;
        padding-top: 2rem;
    }
    .nav1 img{
        border:1px solid white;
        width: 5rem;
        background: white;
        border-radius: 50%;
    }
    .nav2{
      margin-top: 3rem;
      color: white;
    }
    .link{
      color: white;
    }
    .nav2 h2{
      margin-bottom: 2rem;
    }
    .icon{
        color: black;
     
      padding: 1rem;
      font-size: 4rem;
      border-radius: 50%;
      border: 2px solid black;
    }
    .icon2{     
      color: white;
      margin-left: 3rem;
      margin-top: 2rem;
      padding: 1rem;
      font-size: 4rem;
      border-radius: 50%;
      background: #ffbe3c;
    }
  .index{
    background:#ffbe3c ;
    height: 20vh;
    
  }
  .index0{
    display: grid;
    grid-template-columns: 1fr 1fr;
    position: fixed;
    width: 100%;
    margin-bottom: 10rem;
  }
  .index1{
    text-align: right;
    margin-top: 2rem;
    margin-right: 7rem;
    color: white;
  }
  .index1 h2{
    font-size: 50px;
  }
  .index2{
    text-align: center;
  }
  .index2 h1{
      color: white;
    font-size: 100px;
   padding-top: 5rem;
  }
  
  .index2 h2{
    color: white;
    font-size: 50px;
    padding-top: 20rem;
  }
  .et{
      margin-top: 5rem;
      margin-left: 25%;
      margin-right: 25%;
      text-align: center;
  }
  .et1 h2{
      font-size: 70px;
      color:#ffbe3c ;
  }
  .et1 p{
      font-size: 20px;
  }
  .et2{
      margin-top: 3rem;
      display: grid;
      grid-column-gap: 2rem;
      grid-template-columns: 1fr 1fr 1fr;
  }
  .et3 img{
      width: 100%;
      height: 15rem;
  }
  .et4{
      font-weight: bold;
  }
  .et5{
      margin-top: 1.5rem;
      border-top: 1px solid #ffbe3c;
      padding-top: 1rem;
  }
  .et5 p{
      font-size: 20px;
  }
  .et6{
      margin-top: 1rem;
      display: grid;
      grid-column-gap: 2rem;
      grid-template-columns: 1fr 1fr ;
      margin-left: 3rem;
      margin-right: 3rem;
  }
  .et6 img{
      width: 100%;
      height: 15rem;
  }


  @media(max-width:567px){
      .nav{
        width: 100%;
        height: 100vh;
        position: fixed;
        top: 0;
        left: 0;
        background: #ffbe3c;
    }
    .nav1{
        margin-left: 10px;
        margin-right: 10px;
        padding-top: 2rem;
    }
    .nav1 img{
        border:1px solid white;
        width: 5rem;
        background: white;
        border-radius: 50%;
    }
    .icon{
        color: #ffbe3c;
     
      padding: 1rem;
      font-size: 4rem;
      border-radius: 50%;
      background: black;
    }
    .icon2{     
      color: white;
      margin-left: 10px;
      margin-top: 2rem;
      padding: 1rem;
      font-size: 4rem;
      border-radius: 50%;
      background: #ffbe3c;
    }
  
  .index0{
    display: grid;
    grid-template-columns: 1fr 1fr;
  }
  .index1{
    text-align: right;
    margin-top: 2rem;
    margin-right: 10px;
    color: white;
  }
  .index1 h2{
    font-size: 70px;
  }
  .index2{
    text-align: center;
  }
  .index2 h2{
    color: white;
    font-size: 50px;
    padding-top: 15rem;
  }
  .et{
      margin-top: 5rem;
      margin-left: 10px;
      margin-right: 10px;
      text-align: center;
  }
  .et1 h2{
      font-size: 60px;
      color:#ffbe3c ;
  }
  .et1 p{
      font-size: 20px;
  }
  .et2{
      margin-top: 3rem;
      display: grid;
      grid-column-gap: 2rem;
      grid-template-columns: 1fr;
  }
  .et3 img{
      width: 100%;
      height: 15rem;
  }
  .et4{
      font-weight: bold;
  }
  .et5{
      margin-top: 1.5rem;
      border-top: 1px solid #ffbe3c;
      padding-top: 1rem;
  }
  .et5 p{
      font-size: 20px;
  }
  .et6{
      margin-top: 1rem;
      display: grid;
      grid-column-gap: 2rem;
      grid-template-columns: 1fr ;
      margin-left: 0;
      margin-right: 0;
  }
  .et6 img{
      width: 100%;
      height: 15rem;
  }
  }

  @media(min-width:568px) and (max-width:768px){
      .nav{
        width: 40%;
        height: 100vh;
        position: fixed;
        top: 0;
        left: 0;
        background: #ffbe3c;
    }
      .et{
      margin-top: 5rem;
      margin-left: 10%;
      margin-right: 10%;
      text-align: center;
  }
  .et1 h2{
      font-size: 50px;
      color:#ffbe3c ;
  }
  .et1 p{
      font-size: 20px;
  }
  .et2{
      margin-top: 3rem;
      display: grid;
      grid-column-gap: 2rem;
      grid-template-columns: 1fr 1fr 1fr;
  }
  .et3 img{
      width: 100%;
      height: 15rem;
  }
  .et4{
      font-weight: bold;
  }
  .et5{
      margin-top: 1.5rem;
      border-top: 1px solid #ffbe3c;
      padding-top: 1rem;
  }
  .et5 p{
      font-size: 20px;
  }
  .et6{
      margin-top: 1rem;
      display: grid;
      grid-column-gap: 2rem;
      grid-template-columns: 1fr 1fr ;
      margin-left: 3rem;
      margin-right: 3rem;
  }
  .et6 img{
      width: 100%;
      height: 15rem;
  }
  }
</style>

<script>
import FooterSection from '../components/FooterSection.vue';
export default {
  components: { FooterSection },
    data(){
        return{
            act:false,
            
        }
    },
    methods:{
        showNav(){
            if (this.act==true){
                this.act=false;
            }else{
                this.act=true;
               
            }
        },
    }
}
</script>