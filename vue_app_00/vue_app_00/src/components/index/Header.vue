<template>
    <div>
        <div class="left-drop">
            <div class="menu" @click="dropDown">
                <span class="menu-top"></span>
                <span class="menu-middle"></span>
                <span class="menu-bottom"></span>
            </div>
        </div>
        <div id="header">
            <div class="left-header"></div>
            <div class="logo">
                    <a href="javascript:;">
                        <svg viewBox="0 0 3912 1024" class="vivo-brand-logo-small">
                            <use xlink:href="#vivo-brand-logo">
                                <svg id="vivo-brand-logo" viewBox="0 0 3912 1024" width="100%" height="100%"><g><path d="M3522.471385 853.333333H3186.034872C2996.923077 853.333333 2980.105846 697.462154 2980.105846 649.846154 2980.105846 602.230154 2996.923077 446.358974 3186.034872 446.358974h336.436513C3711.596308 446.358974 3728.413538 602.230154 3728.413538 649.846154 3728.413538 697.462154 3711.596308 853.333333 3522.471385 853.333333m7.31241-577.641025H3191.863795C2840.684308 275.692308 2809.439179 562.281026 2809.439179 649.846154 2809.439179 737.411282 2840.684308 1024 3191.863795 1024h337.92C3880.97641 1024 3912.20841 737.411282 3912.20841 649.846154 3912.20841 562.281026 3880.97641 275.692308 3529.783795 275.692308" p-id="661"></path><path d="M2741.894564 301.948718h-109.554872c-46.920205 0-56.582564 7.890051-74.67323 34.382769-18.116923 26.47959-331.460923 498.372923-331.460924 498.372923-10.003692 14.506667-20.611282 20.374974-33.792 20.374975-13.193846 0-23.788308-5.868308-33.778871-20.374975 0 0-313.370256-471.893333-331.474052-498.372923C1809.069949 309.825641 1799.40759 301.948718 1752.487385 301.948718h-109.554872c-25.206154 0-36.758974 19.442872-20.900103 43.191795l374.258872 560.548102C2054.357333 989.945436 2096.971487 1024 2192.413538 1024s138.056205-34.054564 196.135385-118.311385l374.245744-560.548102c15.858872-23.748923 4.332308-43.191795-20.900103-43.191795M1299.69559 347.726769c0-32.794256 12.8-45.778051 45.108513-45.778051h80.462769c32.295385 0 45.095385 12.996923 45.095384 45.778051v630.482052c0 32.794256-12.8 45.791179-45.095384 45.791179h-80.462769C1312.508718 1024 1299.69559 1011.003077 1299.69559 978.208821V347.726769zM1292.973949 147.954872c-26.046359-26.033231-26.046359-46.683897 0-72.730257l55.676718-55.676718c26.046359-26.059487 46.697026-26.059487 72.743384-0.013128l55.702975 55.676718c26.033231 26.059487 26.033231 46.710154 0 72.756513l-55.702975 55.676718c-26.046359 26.046359-46.697026 26.046359-72.730256 0l-55.689846-55.676718zM1126.534564 301.948718h-109.436718c-46.867692 0-56.530051 7.903179-74.594461 34.382769C924.412718 362.811077 611.383795 834.691282 611.383795 834.691282c-9.977436 14.506667-20.571897 20.374974-33.739487 20.374974-13.193846 0-23.775179-5.868308-33.765744-20.374974 0 0-313.028923-471.893333-331.093333-498.372923C194.720821 309.851897 185.058462 301.948718 138.190769 301.948718H28.754051C0.633436 301.948718-7.965538 321.39159 7.880205 345.140513 23.699692 368.902564 381.718974 905.675487 381.718974 905.675487 439.732513 989.945436 482.32041 1024 577.644308 1024c95.310769 0 137.911795-34.054564 195.912205-118.324513L1147.40841 345.140513c15.832615-23.748923 7.246769-43.191795-20.873846-43.191795"></path></g></svg>
                            </use>
                        </svg>
                    </a>
            </div>
            <div class="right-header">
            <router-link class="vp-head-btns-shop" :to="{ path: '/Mall' }" data-head-click-stat="cfrom=1042">
                <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 72 72"><g><path class="st0" d="M57.9,62.7H13.4c-0.1,0-0.1,0-0.2,0c-1.6-0.2-3-1-4-2.2c-1-1.3-1.5-2.8-1.3-4.4l3.5-30c0.4-3.1,2.9-5.3,6-5.3h37c3.1,0,5.6,2.2,6,5.3l3.5,30c0,0.1,0,0.1,0,0.2v0.5C63.9,60,61.2,62.7,57.9,62.7z M13.5,59.7h44.4c1.7,0,3-1.3,3-3v-0.4l-3.5-29.9c-0.2-1.5-1.5-2.7-3-2.7h-37c-1.5,0-2.8,1.1-3,2.7l-3.5,30c-0.1,0.8,0.1,1.6,0.6,2.2C12,59.2,12.7,59.6,13.5,59.7z"></path></g><g><path class="st0" d="M49.5,32.8c-0.8,0-1.5-0.7-1.5-1.5V20.8c0-6.6-5.4-12-12-12c-6.6,0-12,5.4-12,12v10.4c0,0.8-0.7,1.5-1.5,1.5S21,32,21,31.2V20.8c0-8.3,6.7-15,15-15c8.3,0,15,6.7,15,15v10.5C51,32.1,50.3,32.8,49.5,32.8z"></path></g></svg>
            </router-link>
        </div>
        </div>
        <div id="dropContent" class="hide">
            <span class="close"></span>
            <div>
                <img class="search" src="../../assets/img/search-grey.png" @click="search">
                <input type="text" placeholder="iQoo" @focus="keyWord" v-model="search">
            </div>
            <router-link :to="{path:'/Cart'}"><img class="cart" src="../../assets/img/cart-grey.png"></router-link>
        </div>
    </div>
</template>
<script>
export default {
    data() {
        return {
            search:""
        }
    },
    methods:{
        dropDown(){
            var leftDrop=document.getElementsByClassName("left-drop")[0];
            var top=document.getElementsByClassName("menu-top")[0];
            var bottom=document.getElementsByClassName("menu-bottom")[0];
            var middle=document.getElementsByClassName("menu-middle")[0];
            var dropContent=document.getElementById("dropContent");
            if(dropContent.className=="hide"){
                console.log(111);
                dropContent.className="";
                top.style.transform="rotate(45deg) translate(38%)";
                top.style.backgroundColor="#999";
                bottom.style.transform="rotate(-45deg) translate(38%)";
                bottom.style.backgroundColor="#999";
                middle.style.transform="translate(-5vw) scale(0)";
                middle.style.backgroundColor="#999";
            }else if(dropContent.className==""){
                dropContent.className="hide";
                top.style.transform="";
                top.style.backgroundColor="#fff";
                bottom.style.transform="";
                bottom.style.backgroundColor="#fff";
                middle.style.transform="";
                middle.style.backgroundColor="#fff";
            }
        },
        keyWord(){
            var search=document.getElementsByClassName("search")[0];
            var cart=document.getElementsByClassName("cart")[0];
            search.style.right="6vw";
            search.style.height="6vw";
            search.style.marginTop="1vw";
            cart.style.display="none";
        },
        // check(){
        //     var search=document.getElementsByClassName("search")[0];
        //     var cart=document.getElementsByClassName("cart")[0];
        //     search.style.right="";
        //     search.style.height="4vw";
        //     search.style.marginTop="2.5vw";
        //     // cart.style.display="block";
        // }
    }
}                                                                                                    
</script>
<style>
    @import url("../../assets/css/header.css");
</style>