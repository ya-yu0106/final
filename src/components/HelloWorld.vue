<template>
  <body>
    <div class="first"></div>



    <div class="first_art">
      <h1>藝術學院</h1>
    </div>
    <div class="first_nthu">清華大學</div>

    <div class="Second">
      <div class="el"></div>
      <p class="el_pic"></p>
      <p class="el_tri"></p>
      <a class="el_word">Exhibition   &   Lecture</a>
      <a class="el_title">近期展演</a>
      <a class="el_insF">勾勒《新竹・城市美術館》論壇</a>
      <a class="el_insS"
        >奧斯卡獎得主Dr. Jos Stam ：
        我的學習歷程——電腦圖像三十年——從開天闢地到奧斯卡獎的旅程</a
      >
      <a class="el_insT">國際跨領域學術論壇：意識、情感認知與體現互動藝術</a>
      <a class="el_insFO"
        >歡迎報名「跨國實驗時工作坊」：互動藝術中的沈浸式即興創作</a
      >
      <a class="el_insFI">跨系的藝術結晶——2019音樂系三便士歌劇</a>
      <a class="el_insSi"
        >科技藝術策展人講座系列 ： Metabolism at Contemporary</a
      >
    </div>

    <div class="Third">
      <div class="third"></div>
      <p class="third_head"></p>
      <a class="third_head_word">清華大學藝術與設計研究生論文研討會徵稿</a>

      <p class="third_f"></p>
      <a class="f_word">2021年藝術學院教育發展基金</a>
      <p class="third_s"></p>
      <a class="s_word">藝設系學生獲獎—— 
109年林務局「國產材設計商品比賽」</a>
      <p class="third_t"></p>
      <a class="t_word">清華藝術學報徵稿</a>
      <p class="third_fo"></p>
      <a class="fo_word">藝術學院畢業典禮</a>
      <p class="third_head_pic"></p>
      <p class="third_button"></p>
      <a class="but_word">more...</a>
      <a class="third_news">最新消息</a>
      <p class="third_set"></p>
      <p class="third_set_o"></p>
      <p class="third_set_t"></p>
      <p class="third_set_thr"></p>

    </div>

    <div class="Four">
    <div class="four"></div>  
    <a class="nthu_w">國立清華大學藝術學院 | TEL: +886-3-5717131 #78801 | 2020 Copyright©</a>
    </div>

    <div class="Dock">
    <p class="dock"></p>
      <a class="dock_home" href="http://localhost:8080" target="_current">
        首頁
      </a>

      <a
        class="dock_about"
        href="http://localhost:8080/#/AboutMe"
        target="_current"
      >
        關於學院
      </a>
      <p class="dock_logo"></p>
      <a class="dock_rules">
        學院規章
      </a>
      <a class="dock_requr">
        招生訊息
      </a>
      <a class="dock_honor">
        榮譽榜
      </a>
      <a class="dock_activ">
        活動花絮
      </a>
      <a class="dock_media">
        藝院影音
      </a>
      <a class="dock_report">
        藝術學報
      </a>
      <a class="dock_cont">
        聯絡資訊
      </a>
    </div>

    <div class="little"></div>
  </body>
</template>



<script>
export default {
  name: "HelloWorld",
  data() {
    return {
      nthuUrl: "../assets/清華大學logo.jpg",
      // msg:'Welcome!' //<h1>{{ msg }}</h1>
      elUrl: "../assets/1.png",
      thirdhead_pic: "../assets/head.png"
    };
  }
};
</script>



<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.first {
  /*body{
/* Rectangle 15 */
  position: absolute;
  width: 1440px;
  height: 751px;
  left: 0px;
  top: 0px;

  background: linear-gradient(
      180deg,
      #272327 0%,
      rgba(196, 183, 194, 0.823) 0%,
      rgba(255, 255, 255, 0) 100%
    ),
    #282623;
}
</style>

<style scoped>

.Dock{
    width: 1440px;
    margin:0px auto;
    font-family: Athiti;
  font-style: normal;
  font-weight: 450;
  font-size: 14px;
  line-height: 29px;
    color: #625b5b;


}
.dock {
  /* Rectangle 1 */
  margin: auto;
  position: absolute;
  width: 1440px;
  height: 93px;
  left: 0px;
  top: -1px;

  background: #ffffff;
  mix-blend-mode: normal;
  font-family: Athiti;
  font-style: normal;
  font-weight: 00;
  font-size: 14px;
  line-height: 29px;
  /* identical to box height */

  letter-spacing: 0.075em;
  color: #625b5b;
}
.dock_logo {
  /* 清華大學logo 1 */
  background: url("../assets/清華大學logo.jpg");

  position: absolute;
  width: 300px;
  height: 66px;
  left: 36px;
  top: 3px;
}
.dock_home {
    text-decoration: none;

  position: absolute;
  width: 48px;
  height: 29px;
  left: 690px;
  top: 34px;
    color: #625b5b;

}

.dock_about {
  /* 2 */
      text-decoration: none;

  position: absolute;
  width: 77px;
  height: 29px;
  left: 750px;
  top: 34px;
    color: #625b5b;

}

.dock_rules {
  /* 3 */
  position: absolute;
  width: 77px;
  height: 29px;
  left: 835px;
  top: 34px;
}
.dock_requr {
  /* 4 */
  position: absolute;
  width: 77px;
  height: 29px;
  left: 915px;
  top: 34px;
}
.dock_honor {
  position: absolute;
  width: 57px;
  height: 29px;
  left: 1000px;
  top: 34px;
}
.dock_activ {
  position: absolute;
  width: 77px;
  height: 58px;
  left: 1060px;
  top: 34px;
}
.dock_media {
  position: absolute;
  width: 77px;
  height: 29px;
  left: 1140px;
  top: 34px;
}
.dock_report {
  position: absolute;
  width: 77px;
  height: 58px;
  left: 1220px;
  top: 34px;
}
.dock_cont {
  position: absolute;
  width: 77px;
  height: 29px;
  left: 1300px;
  top: 34px;
}
.first_nthu{
    /* 清華大學 */


position: absolute;
width: 250px;
height: 48px;
left: 844px;
top: 560px;

font-family: Athiti;
font-style: 400;
font-weight: normal;
font-size: 36px;
line-height: 53px;
letter-spacing: 0.34em;

color: #FFFFFF;
}
.first_art {
  /* 藝術學院 */

  position: absolute;
  width: 644px;
  height: 158px;
  left: 753px;
  top: 550px;

font-family: Athiti;
  font-weight: 400;
  font-size: 45px;
  line-height: 141px;
  letter-spacing: 0.34em;

  color: #ffffff;
}
</style>

<style scoped>
.el {
    margin:0;padding:0;
  /* Rectangle 21 */
  position: absolute;
  width: 17px;
  height: 646px;
  left: 0px;
  top: 751px;

  background: #747474;
}
.el_pic {
  position: absolute;
  width: 940px;
  height: 400px;
  left: 471px;
  top: 931px;
  background: url("../assets/1.png");
}

.el_tri {
  /* Polygon 1 */

  position: absolute;

  left: 70.75px;
  top: 1000px;

  width: 0;
  height: 0;
  border-style: solid;
  border-width: 5px 0 5px 8.7px;
  border-color: transparent transparent transparent #000000;
}

.el_word {
  /* Exhibition Lecture */

  position: absolute;
  width: 1390px;
  height: 122px;
  left: 83px;
  top: 788px;

  font-family: Athiti ;
  font-style: normal;
  font-weight: bold;
  font-size: 64px;
  line-height: 116px;
  letter-spacing: 0.36em;
  white-space: nowrap;
  display: inline;
  text-align: left;

  background: linear-gradient(148.38deg, #2F2C29 27.52%, rgba(49, 49, 49, 0) 102.93%),
linear-gradient(0deg, #bdbbb9, #FAFAFA);
-webkit-background-clip: text;
-webkit-text-fill-color: transparent;

}
.el_title {
  /* 近期展演 */

  position: absolute;
  width: 156px;
  height: 44px;
  left: 83px;
  top: 931px;

  font-family: Athiti;
  font-style: normal;
  font-weight: 500;
  font-size: 24px;
  line-height: 38px;
  letter-spacing: 0.26em;

  color: #000000;
  text-align: left;
}
.el_insF {
  /* 勾勒《新竹・城市美術館》論壇 */

  position: absolute;
  width: 262px;
  height: 21px;
  left: 83px;
  top: 1010px;

  font-family: Athiti;
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 22px;
  letter-spacing: 0.075em;

  color: #000000;
  white-space: pre-wrap;
  text-align: left;
}
.el_insS {
  /* 奧斯卡獎得主Dr. Jos Stam ： 我的學習歷程——電 腦圖像三十年——從開天闢地到奧斯卡獎的旅程 */

  position: absolute;
  width: 340px;
  height: 45px;
  left: 83px;
  top: 1046px;

  font-family: Athiti;
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 22px;
  letter-spacing: 0.075em;

  color: #000000;
  text-align: left;
}
.el_insT {
  /* 國際跨領域學術論壇：意識、情感認知與體現互動藝術 */

  position: absolute;
  width: 340px;
  height: 49px;
  left: 83px;
  top: 1106px;

  font-family: Athiti;
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 22px;
  letter-spacing: 0.075em;

  color: #000000;
  text-align: left;
}
.el_insFO {
  /* 歡迎報名「跨國實驗時工作坊」：互動藝術中的沈浸式即興創作 */

  position: absolute;
  width: 340px;
  height: 49px;
  left: 83px;
  top: 1170px;

  font-family: Athiti;
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 22px;
  letter-spacing: 0.075em;

  color: #000000;
  text-align: left;
}
.el_insFI {
  /* 跨系的藝術結晶——2019音樂系三便士歌劇 */

  position: absolute;
  width: 330px;
  height: 21px;
  left: 83px;
  top: 1234px;

  font-family: Athiti;
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 22px;
  letter-spacing: 0.075em;

  color: #000000;
  text-align: left;
}
.el_insSi {
  /* 科技藝術策展人講座系列 ： Metabolism at Contemporary */

  position: absolute;
  width: 351px;
  height: 49px;
  left: 83px;
  top: 1270px;

  font-family: Athiti;
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 22px;
  letter-spacing: 0.075em;

  color: #000000;
  text-align: left;
}
</style>



<style scoped>
.third {
  /* Rectangle 17 */
  margin: auto;
  position: absolute;
  width: 1440px;
  height: 862px;
  left: 0px;
  top: 1397px;

  background: linear-gradient(360deg, #d1d1d1 0%, rgba(255, 255, 255, 0) 100%),
    #474747;
}
.third_button {
  /* Rectangle 8 */

  position: absolute;
  width: 107px;
  height: 33px;
  left: 667px;
  top: 2088px;

  background: #413d3d;
}
.but_word {
  /* more... */

  position: absolute;
  width: 70px;
  height: 17px;
  left: 685px;
  top: 2104px;

  font-family: Athiti;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 29px;
  letter-spacing: 0.15em;

  color: #dbdbdb;
}
.third_set{
    /* Group 3 */
height: 27px;
width: 173px;
left: 1174px;
top: 1438px;
border-radius: 12px;

border: 1px solid rgba(255, 255, 255, 1);
position: absolute;
width: 173px;
height: 27px;
left: 1174px;
top: 1438px;

    
}
.third_set_o{
    /* Line 6 */
height: 0px;
width: 29px;
left: 1379px;
top: 1463px;
border-radius: nullpx;

border: 2px solid rgba(255, 255, 255, 1);
position: absolute;

border: 2px solid #FFFFFF;
}
.third_set_t{
    height: 0px;
width: 29px;
left: 1379px;
top: 1452.41px;
border-radius: nullpx;
border: 2px solid rgba(255, 255, 255, 1);
border: 2px solid #FFFFFF;
position: absolute;
}
.third_set_thr{
/* Line 4 */
width: 29px;
left: 1379px;
top: 1441px;
border-radius: nullpx;

border: 2px solid rgba(255, 255, 255, 1);
position: absolute;
width: 29px;
height: 0px;
left: 1379px;
top: 1441px;

border: 2px solid #FFFFFF;

}
.third_news{
    /* 最新消息 */


position: absolute;
width: 156px;
height: 42px;
left: 663px;
top: 1438px;

font-family: Athiti;
font-style: normal;
font-weight: 500;
font-size: 24px;
line-height: 38px;
letter-spacing: 0.26em;

color: #FFFFFF;

}
.third_head {
  /* 最新消息 徵稿 */

  position: absolute;
  width: 683.15px;
  height: 421.11px;
  left: 81px;
  top: 1547px;

  background: rgba(255, 255, 255, 0.8);
  background-blend-mode: lighten;
  border-radius: 13px;
}
.third_head_pic {
  position: absolute;
  width: 620.63px;
  height: 297.68px;
  left: 112.26px;
  top: 1572.93px;

  background: url("../assets/head.png");
}
.third_head_word {
  /* 清華大學藝術與設計研究生論文研討會徵稿 */

  position: absolute;
  width: 610.52px;
  height: 41.49px;
  left: 116.86px;
  top: 1901.73px;

  font-family: Athiti;
  font-style: normal;
  font-weight: 370;
  font-size: 24px;
  line-height: 38px;
  letter-spacing: 0.195em;

  color: #000000;
}
.third_f {
  /* Rectangle 19 */

  position: absolute;
  width: 493.75px;
  height: 82.75px;
  left: 785.3px;
  top: 1547px;

  background: rgba(255, 255, 255, 0.8);
  background-blend-mode: lighten;
  border-radius: 13px;
}
.f_word {
  /* 2021年藝術學院教育發展基金 */

  position: absolute;
  width: 610.52px;
  height: 36.78px;
  left: 817.48px;
  top: 1579.99px;

  font-family: Athiti;
  font-style: normal;
  font-weight: 370;
  font-size: 22px;
  line-height: 38px;
  letter-spacing: 0.195em;

  color: #000000;
  text-align: left;
}
.third_s {
  /* Rectangle 20 */

  position: absolute;
  width: 493.75px;
  height: 120.45px;
  left: 785.3px;
  top: 1647.22px;

  background: rgba(255, 255, 255, 0.8);
  background-blend-mode: lighten;
  border-radius: 13px;
}
.s_word {
  /* 藝設系學生獲獎—— 109年林務局「國產材設計商品比賽」 */

  position: absolute;
  width: 610.52px;
  height: 36.78px;
  left: 806.45px;
  top: 1683.88px;

  font-family: Athiti;
  font-style: normal;
  font-weight: 370;
  font-size: 22px;
  line-height: 38px;
  letter-spacing: 0.195em;

  color: #000000;
  text-align: left;
  white-space: pre-wrap;
}
.third_t {
  /* Rectangle 20 */

  position: absolute;
  width: 493.75px;
  height: 83.67px;
  left: 785.3px;
  top: 1785.14px;

  background: rgba(255, 255, 255, 0.8);
  background-blend-mode: lighten;
  border-radius: 13px;
}
.t_word {
  /* 清華藝術學報徵稿 */

  position: absolute;
  width: 472.6px;
  height: 45.05px;
  left: 806.45px;
  top: 1820.88px;

  font-family: Athiti;
  font-style: normal;
  font-weight: 370;
  font-size: 22px;
  line-height: 38px;
  letter-spacing: 0.195em;

  color: #000000;
  text-align: left;
}
.third_fo {
  /* Rectangle 20 */

  position: absolute;
  width: 493.75px;
  height: 83.67px;
  left: 785.3px;
  top: 1884.44px;

  background: rgba(255, 255, 255, 0.8);
  background-blend-mode: lighten;
  border-radius: 13px;
}
.fo_word {
  /* 藝術學院畢業典禮 */

  position: absolute;
  width: 472.6px;
  height: 45.05px;
  left: 806.45px;
  top: 1920.18px;

  font-family: Athiti;
  font-style: normal;
  font-weight: 370;
  font-size: 22px;
  line-height: 38px;
  letter-spacing: 0.195em;

  color: #000000;
  text-align: left;
}


</style>

<style scoped>
.four {
  /* Rectangle 22 */

  position: absolute;
  width: 1453px;
  height: 108px;
  left: 0px;
  top: 2256px;

  background: #ffffff;
}
body {
        margin:0;padding:0;

}
.nthu_w{
    /* 國立清華大學藝術學院 */


position: absolute;
width: 1440px;
height: 43px;
left: 35px;
top: 2297px;

font-family: Athiti;
font-style: normal;
font-weight: 400;
font-size: 18px;
line-height: 29px;
letter-spacing: 0.195em;

color: #000000;

}
.ltitle{

/* Line 8 */
border: 1px solid rgba(69, 69, 69, 1);

position: absolute;
width: 554.89px;
height: 0px;
left: 373px;
top: 0px;
height: 0px;

border-radius: 0px;

border: 1px solid #454545;
transform: rotate(132.52deg);


}
</style>


