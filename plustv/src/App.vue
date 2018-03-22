<template>
  <div id="app">
<nav class="nav">
        <div class="menu-bar">
            <div>
                <div class="img"></div>
                </div>
                <div class="nav-menu" >
                    <div>{{ about }}</div>
                    <div>{{service}}</div>
                    <div>{{gallery}}</div>
                    <div>{{contact}}</div>
                </div>
        </div>
    </nav>

    <div id="main">
      <div id="maintypo" ><span>Plus TV</span>는<br/>디스플레이를 통해<br/>고객에게 <span>새로운 가치</span>를<br/>제공합니다.</div>
      
      <div id="maininfo">

        <div class="icons">

          <div id="icons1" class="iconop"></div>
          <div class="icontext" v-html="maintypo1"></div>
        </div>
        <div class="icons">

          <div id="icons2" class="iconop"></div>
          <div class="icontext" v-html="maintypo2"></div>
        </div>
        <div class="icons">

          <div id="icons3" class="iconop"></div>
          <div class="icontext" v-html="maintypo3"></div>
        </div>
        <div class="icons">

          <div id="icons4" class="iconop"></div>
          <div class="icontext" v-html="maintypo4"></div>
        </div>
      </div>
      </div>
<div id="main2">
<div id="main2-1">
<div id="main2-1naeyoung">
<div id="greenline"></div>
<div id="vision" v-html="vision"></div>
<div id="visionar" v-html="visionar"></div>
</div>
</div>
<div id="main2-2">
  <div id="main2-img"></div>
</div>
<div id="main3">
<div id="main3-1">


</div>
<div id="main3-2">


  
</div>

</div>





</div>

</div>
</template>

<script>
export default {
  name: "#app",
  data() {
    return {
      name: "PLUS TV",
      about: "ABOUT",
      service: "SERVICE",
      gallery: "GALLERY",
      contact: "CONTACT",
      maintypo1: "손쉽게 제품을 <br/> 홍보할 수 있습니다.",
      maintypo2: "고객의 목표에 맞는 <br/> 최적의 소프트웨어를 제공합니다.",
      maintypo3:
        "모바일과 PC를 통해서 <br/> 전세계 디스플레이를 모니터링 가능합니다.",
      maintypo4:
        "전세계 어디에 있든 인터넷만 된다면 <br/> 손쉽게 디스플레이를 관리할 수 있습니다",
        vision : 'PLUS TV<br/>Vision',
        visionar : '철저한 고객 분석을 통해<br/>디스플레이 소프트웨어 시장에<br/>고객에게 유익한 가치를 제공할 수 있는<br/>글로벌 회사를 만들어 보겠습니다.'
    };
  }
};
</script>

<style >

</style>
