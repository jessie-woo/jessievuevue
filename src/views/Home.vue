<template>
<body>
  <div class="circle circle1"></div>
  <div class="circle circle2"></div>
  <div class="border-top">
    <h4>DO YOU LIKE CODING ? STAYING UP LATE ?</h4>
    <h6>藝 術 學 院 學 士 班</h6><br>
  </div>
  <div class="藝術學院學士班">
    <HelloWorld msg="院學士班最新消息"/>
  </div>
  <div class="namecard">
    <h1>. 學士班特色 .</h1>
    <hr>
    <p>清華是國際頂尖科技大學，加上合校後的藝術學院，具</p>
    <p>備發展「科技藝術」的卓越條件。我們號召臺灣年輕一</p>
    <p>代的科技藝術學者專家，我們規劃有科技藝術跨域特別</p>
    <p>課程，並與業界合作推出創意跨域專題。</p>
    <p>你，不需猶豫，歡迎你的加入！</p>
  </div>
  <div class="namecard2">
    <h1>. 核心能力 .</h1>
    <hr>
    <br>
    <p>社會關懷與品格實踐能力 ｜ 美感認知與經典欣賞能力</p>
    <p>自然感知與創新發想能力 ｜ 邏輯思辨與語文溝通能力</p>
    <p>國際觀點與在地行動能力 ｜ 資訊掌握與科技應用能力</p>
  </div>
  <div class="namecard3">
    <br>
    <p>清華大學2018年成立藝術學院〝科技藝術〞跨域「學士班」。</p>
    <p>「科技藝術（TechArt）」是當代藝術的新形式創作也是國際藝</p>
    <p>術發展的重要趨勢，包含虛擬藝術、互動藝術、電腦動畫、電腦</p>
    <p>音樂、聲音藝術、科技性表演藝術、混合藝術、網路社群、創客</p>
    <p>藝術、仿生藝術、生物藝術、人工生命…等。在當代數位美學與</p>
    <p>數位藝術的基礎下，我們結合創新科技，如各種互動感測技術、</p>
    <p>虛擬實境、物聯網、人工智慧、大數據分析、基因工程…，把「科</p>
    <p>技」與「藝術」結合視為「未來文化學」，培養前瞻性、跨域研</p>
    <p>究與創作人才。</p>
    <br>.<hr>.<br><br>
    <p>因應未來產業的發展趨勢，創新科技與當代藝術結合之創作如雨後</p>
    <p>春筍。清華大學的是國內科學與科技的頂尖學府，對藝術學院發展</p>
    <p>「科技藝術」具有得天獨厚的優勢。本班師資除來自清華校內藝術</p>
    <p>學院、電資學院、工學院、生命科學院、人文社會等跨域教師外，</p>
    <p>我們也將聘進一群來自美國、歐洲與日本跨國與跨域的專業教師。</p>
    <p>也廣邀在臺灣在科技藝術創作領域最頂尖的業界團隊與藝術家加入</p>
    <p>我們的教學團隊，讓同學得到專業與多元的指導，並在共享學習、</p>
    <p>共享創意的環境裡，開創未來的產業，盡情發揮自己的潛能。</p>
  </div>
  </body>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}

</script>

<style>
.circle{
  width: 100px;
  height: 100px;
  border-radius: 100%;
  position: absolute;
 
  
}
.circle1{
  right: 100px;
  top:200px;
  background-color: #FF9CB0;
/*   bottom: -60px; */
}

.circle2{
  width: 60px;
  height: 60px;
  right: 200px;
  top:300px;
  border: solid 3px #FF9CB0;
}
.border-top{
  padding:10px;
  margin:0px;
  height: 50vh;
  width: 100vw;
  position:center;
  background-color:#0b525b;

}
.border-top h6{
  font-size:80px;
  bottom: 200px;
  font-weight:bold;
  color:#ffff;
  text-align:center;
}
.namecard p{
  text-align:left 20px;
}
.namecard p{
  text-align:right 20px;
}


.藝術學院學士班{
  padding:50px;
  font-weight: bold;
}
.namecard {
      background-color:#FF9CB0;
      color:#000000;
      width: 500px;
      height: 300px;
      position: absolute;
      top: 600px;
      left:-15px;
      z-index: 99999;
      box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.2);
      border-radius: 8px;
      padding: 10px;
    }
.namecard2 {
      background-color:#faedcd;
      color:#000000;
      width: 500px;
      height: 280px;
      position: absolute;
      top: 1000px;
      left:-15px;
      z-index: 99999;
      box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.2);
      border-radius: 8px;
      padding: 10px;
    }
.namecard3 {
      background-color:#219ebc;
      color:#ffff;
      width: 500px;
      height: 900px;
      position: absolute;
      top: 600px;
      right:-25px;
      z-index: 99999;
      box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.2);
      border-radius: 8px;
      padding: 10px;
    }  

</style>