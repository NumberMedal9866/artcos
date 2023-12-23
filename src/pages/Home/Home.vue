<template>
            <div class="logo-mob">
                <img src="@/assets/images/logoThree.png" alt="">
            </div>
    <header class="headerr container">
        <div class="container">
            <div class="title">
                <h1>Artcos</h1>
                <h1>Co., LTD.</h1>
            </div>
            <div class="title-ad">
                <div class="title-ad-f title-ad-s">
                    <span>Artcos</span>
                    <img src="@/assets/images/handshake.svg" alt="">
                </div>
                <div class="title-ad-s">
                    <span>Co.,</span>
                    <h3>LTD.</h3>
                <div class="effectt">
                    <div ref="blob al" class="blobb al"></div>
                </div>
                </div>
            </div>
            <p>Artcos provides a variety of innovative and comprehensive IT solutions. We deliver quality services in the most efficient way, and our experts will work collaboratively with you to customize our offerings to your particular needs. Book a meeting with one of our consultants to hear more about how we can assist your operation.</p>
            <div class="btn-holder">
                <div><router-link to="/services">See our services</router-link></div>
                <div><router-link to="/contact">Our info</router-link></div>
            </div>
            <img class="avatar" src="@/assets/images/logoThree.png" alt="">
        </div>
    </header>
    <!-- тут я удалииииллллл -->
    <section class="container"> 
        <div class="container">
            <h2 class="work">About us</h2>
            <div class="card-holder">
                <div class="card hidden">
                    <div class="card-info">
                        <!-- <img src="@/assets/images/Subbi.svg" alt=""> -->
                        <h3>What we do</h3>
                        <p>Forest Group Company LTD operates in the markets of digital, industrial, and construction products. Despite its relatively short existence, the company holds a significant position in the market, contributing to the rapid development of the country's economy. The main focus lies in supplying equipment, materials, spare parts, and special equipment to businesses of varying sizes. Our operations extend to countries like China, South Korea, Taiwan, Thailand, UAE, CIS, USA, and EU member states. Notably, we maintain no direct or indirect associations with countries included in the sanctions list (OFAC).</p>
                        <!-- <a href="https://vuecinephile.vercel.app/#/" target="_blank">Visit site</a> -->
                        <router-link to="/services">Our services ➔</router-link>
                    </div>
                    <img src="@/assets/images/logo.png" alt="" class="card-info-img proj">
                </div>
                <div class="card hidden">
                    <div class="card-info">
                        <!-- <img src="@/assets/images/Subbi.svg" alt=""> -->
                        <h3>Thriving in Digital Appliance Innovation</h3>
                        <p class="alter">The production and sale of digital and home appliances stand as promising sectors in our activities. This domain is highly competitive, encompassing personal computers, smartphones, tablets, laptops, and other high-tech equipment integral to modern life. Beyond product supply, our company offers comprehensive transportation services for goods worldwide via any mode of transport. While we cover a broad spectrum of transport services, our primary focus remains on delivering cargo according to the most convenient and cost-effective scheme for the cargo owner. Additionally, we specialize in sourcing necessary products or partners, installation, supervision, and technical support for supplied products. As a young but rapidly evolving company, we've forged partnerships with major manufacturers. Our core ethos centers on being customer-oriented, constantly striving for improvement in this direction. Our team's reality reflects a multitude of successfully completed orders, a robust base of loyal customers, collaborations with industry leaders, and an unwavering commitment to service quality.</p>
                        <router-link to="/services">Our services ➔</router-link>
                    </div>
                    <!-- <img src="@/assets/images/pearlogo.png" alt="" class="card-info-img project"> -->
                </div>

            </div>
        </div>
    </section>
    <!-- <section class="about container">
        <div class="container">
            <h2 class="card-catalog-title">Get to know me</h2>
            <div class="card-catalog">
                <router-link to="/about" class="infocard">
                    <h3>About me</h3>
                    <span>Who I am and what I do</span>
                    <img src="@/assets/images/avaa.png" alt="" class="infocard-img">
                </router-link>
                <router-link to="/tech" class="infocard">
                    <h3>Tech Stack</h3>
                    <p>The dev tools, apps, devices, and games I use and play.</p>
                    <img src="@/assets/images/tech-stack.svg" alt="" class="infocard-tech">
                </router-link>
                <router-link to="/contact" class="infocard">
                    <h3>Contact me</h3>
                    <span>My contacts and social</span>
                    <img src="@/assets/images/phone.svg" alt="" class="infocard-img2">
                </router-link>
                <router-link to="/about" class="infocard">
                    <h3>My list of projects</h3>
                    <p>All of my finished projects</p>
                    <img src="@/assets/images/proj.svg" alt="" class="infocard-proj">
                </router-link>
            </div>
        </div>
    </section> -->

</template>

<script setup>
    import { ref, onMounted, onBeforeUnmount } from 'vue';

const observer = ref(null); // Initialize the observer as null

// Define a function to initialize the Intersection Observer
const initializeObserver = () => {
  observer.value = new IntersectionObserver((entries) => {
    entries.forEach((entry) => {
      if (entry.isIntersecting) {
        entry.target.classList.add('show');
      } else {
        entry.target.classList.remove('show');
      }
    });
  });
};

// Call the initializeObserver function when the component is mounted
onMounted(() => {
  initializeObserver();
  const hiddenElements = document.querySelectorAll('.hidden');
  hiddenElements.forEach((el) => observer.value.observe(el));
});

// Clean up the observer when the component is unmounted
onBeforeUnmount(() => {
  if (observer.value) {
    observer.value.disconnect();
  }
});
</script>

<style lang="scss" scoped>
    .sdf{
        color: red;
    }
     .projects{
    &-title{
        margin-bottom: 60px;
        span{
            color: #80808080;
            font-family: I4;
            font-weight: 400;
            font-size: 24px;
            letter-spacing: -0.456px;
            // @include media(500){
            //     font-size: 16px;
            // }
        }
    }
 }
 .top{
    margin-top: 60px;
 }
 .proj{
    position: inherit;
    width: 315px;
    margin-left: 100px;
    padding: 20px;
    border-radius: 32px;
    border: 1px solid #383737;
 }
 .project{
    position: inherit;
    width: 280px;
    // height: 200px;
    margin-left: 100px;
    padding: 60px;
    border-radius: 32px;
    border: 1px solid #383737;
    background: white;
 }
</style>