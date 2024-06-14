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
                        <p>AVL Networks Co., LTD operates in the markets of digital, industrial and construction products. The main activity is the supply of mining equipment (lifting and enrichment equipment, vertical sinking and near-shaft yard, mixing and charging machines of the HANFO-REPUMP series, spare parts), digital, industrial and construction equipment and materials, spare parts and special equipment for large, medium and small businesses. Despite the relatively short period of its existence, the company occupies a certain position in the market and contributes to the rapidly developing economy of the country. </p>
                        <!-- <a href="https://vuecinephile.vercel.app/#/" target="_blank">Visit site</a> -->
                        <router-link to="/services">Our services ➔</router-link>
                    </div>
                    <img src="@/assets/images/logo.png" alt="" class="card-info-img proj">
                </div>
                <div class="card hidden">
                    <div class="card-info">
                        <!-- <img src="@/assets/images/Subbi.svg" alt=""> -->
                        <h3>Countries we work with</h3>
                        <p>Our company works with countries such as: China, South Korea, Taiwan, Thailand, UAE, CIS, USA and EU member states. 
                        The company is not directly or indirectly associated with the countries included in the sanctions list (OFAC).                                                           
                        </p>
                        <!-- <a href="https://vuecinephile.vercel.app/#/" target="_blank">Visit site</a> -->
                        <router-link to="/services">Our services ➔</router-link>
                    </div>
                    <img src="@/assets/images/world.svg" alt="" class="card-info-img proj">
                </div>
                <div class="card hidden">
                    <div class="card-info">
                        <!-- <img src="@/assets/images/Subbi.svg" alt=""> -->
                        <h3>Provided services</h3>
                        <p class="alter uno">
                            Production and sale of digital and home appliances is a promising area of activity. Companies that are engaged in such business, note a very high level of competition in their field. 
                            Personal computers, smartphones, tablet computers, laptops and other high-tech equipment are quite common, without which it is difficult to imagine the life of a modern person.<br><br>

                            Our company provides a full range of services for the transportation of any goods from anywhere in the world by any type of transport. With all the quantitative breadth of transport services provided, the main function of the company's activities remains unchanged – cargo delivery according to the most convenient and economical scheme for the cargo owner. <br><br>

                            Our company also provides services for finding the necessary products or partners, installation, installation supervision and technical support of the supplied products.     <br><br>

                            We are a young, but rapidly developing company that has partnered with major manufacturers.<br><br>  

                            “Our company is, first of all, customer-oriented and we do everything possible to improve, first of all, in this direction.<br><br>ё 

                            “The reality of our team is a huge number of successfully completed orders, a wide base of regular customers, cooperation with leading companies and impeccable quality of services.                                                      
                        </p>
                        <p class="alter dos">
                            Production and sale of digital and home appliances is a promising area of activity. Companies that are engaged in such business, note a very high level of competition in their field. 
                            Personal computers, smartphones, tablet computers, laptops and other high-tech equipment are quite common, without which it is difficult to imagine the life of a modern person.  

                            Our company provides a full range of services for the transportation of any goods from anywhere in the world by any type of transport. With all the quantitative breadth of transport services provided, the main function of the company's activities remains unchanged – cargo delivery according to the most convenient and economical scheme for the cargo owner. 

                            Our company also provides services for finding the necessary products or partners, installation, installation supervision and technical support of the supplied products.     

                            We are a young, but rapidly developing company that has partnered with major manufacturers.  

                            “Our company is, first of all, customer-oriented and we do everything possible to improve, first of all, in this direction. 

                            “The reality of our team is a huge number of successfully completed orders, a wide base of regular customers, cooperation with leading companies and impeccable quality of services.                                                                           
                        </p>
                        <router-link to="/services">Our services ➔</router-link>
                    </div>
                    <!-- <img src="@/assets/images/pearlogo.png" alt="" class="card-info-img project"> -->
                </div>

            </div>
        </div>
    </section>
    <section class="container">
        <div class="container">
            <h2 class="work gap">Our contact information</h2>
            <div class="message">
                <div class="message-nav">
                    <img src="@/assets/images/mac.svg" alt="">
                    <p>Our contact information</p>
                </div>
                <div class="message-main">
                    <form @submit.prevent="handleSubmit" ref="form">
                        <div class="message-main-input">
                            <span>Email:</span>
                            <span>info@artcosgrp.com</span>
                        </div>
                        <div class="message-main-input">
                            <span>Number:</span>
                            <span>+66 820 780 002</span>
                        </div>
                        <div class="message-main-input">
                            <span>Tax Id Number:</span>
                            <span>0105565005522</span>
                        </div>
                        <span class="message-main-address">Address:</span>
                        <iframe class="fir" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1937.8869259157639!2d100.56511820732361!3d13.7321468298223!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x30e29f028e9e1de7%3A0xb100bede8f20a1ad!2s25%20Sukhumvit%20Rd%2C%20Khwaeng%20Khlong%20Tan%2C%20Khet%20Khlong%20Toei%2C%20Krung%20Thep%20Maha%20Nakhon%2010110%2C%20Thailand!5e0!3m2!1sen!2s!4v1703347367752!5m2!1sen!2s" width="100%" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
                        <iframe class="nd" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1937.8869259157639!2d100.56511820732361!3d13.7321468298223!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x30e29f028e9e1de7%3A0xb100bede8f20a1ad!2s25%20Sukhumvit%20Rd%2C%20Khwaeng%20Khlong%20Tan%2C%20Khet%20Khlong%20Toei%2C%20Krung%20Thep%20Maha%20Nakhon%2010110%2C%20Thailand!5e0!3m2!1sen!2s!4v1703347367752!5m2!1sen!2s" width="100%" height="300" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
                    </form>
                </div>
            </div>
        </div>
    </section>
    <div class="header-line"></div>
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
//  .proj-two{
//     position: inherit;
//     width: 315px;
//     margin-left: 100px;
//     padding: 20px;
//     padding: 10px 0;
//     border-radius: 32px;
//     border: 1px solid #383737;
//     // height: 50px;
//  }
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