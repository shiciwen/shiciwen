<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>

  <nav class="navbar navbar-expand mb-5">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Navbar</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
        aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Features</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Pricing</a>
          </li>
          <li class="nav-item">
            <a class="nav-link disabled">Disabled</a>
          </li>
        </ul>


      </div>
    </div>
  </nav>

  <div class="scw-container mx-5">
    <div class="row">
      <div class="col-3">
        <div class="wrapper">
          <HelloWorld msg="You did it!" />
        </div>
      </div>
      <div class="col-2">
        <div class="scw-catalogue" style="max-height: 100vh;overflow-y: scroll;">
          <div class="zhengwen">
            <h5>十二本纪</h5>
            <ul class="list-unstyled">
              <li><a href="http://www.uaut.cn/shiji/1655693059.html">五帝本纪</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693049.html">夏本纪</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693039.html">殷本纪</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693030.html">周本纪</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693019.html">秦本纪</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693008.html">秦始皇本纪</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655692997.html">项羽本纪</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655692986.html">高祖本纪</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655692975.html">吕太后本纪</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655692965.html">孝文本纪</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655692955.html">孝景本纪</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655692946.html">孝武本纪</a></li>
            </ul>
            <h4>七十列传</h4>
            <ul class="list-unstyled">
              <li><a href="http://www.uaut.cn/shiji/1655694319.html">伯夷列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655694310.html">管晏列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655694300.html">老子韩非列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655694291.html">司马穰苴列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655694281.html">孙子吴起列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655694272.html">伍子胥列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655694262.html">仲尼弟子列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655694251.html">商君列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655694242.html">苏秦列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655694231.html">张仪列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655694220.html">樗里子甘茂列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655694210.html">穰侯列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655694200.html">白起王翦列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655694191.html">孟子荀卿列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655694181.html">孟尝君列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655694171.html">平原君虞卿列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655694161.html">魏公子列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655694151.html">春申君列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655694141.html">范雎蔡泽列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655694130.html">乐毅列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655694120.html">廉颇蔺相如列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655694110.html">田单列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655694100.html">鲁仲连邹阳列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655694090.html">屈原贾生列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655694081.html">吕不韦列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655694071.html">刺客列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655694060.html">李斯列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655694049.html">蒙恬列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655694040.html">张耳陈馀列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655694030.html">魏豹彭越列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655694020.html">黥布列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655694011.html">淮阴侯列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655694000.html">韩信卢绾列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693990.html">田儋列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693981.html">樊郦滕灌列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693970.html">张丞相列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693960.html">郦生陆贾列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693950.html">傅靳蒯成列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693941.html">刘敬叔孙通列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693931.html">季布栾布列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693922.html">袁盎晁错列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693912.html">张释之冯唐列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693903.html">万石张叔列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693893.html">田叔列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693884.html">扁鹊仓公列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693873.html">吴王濞列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693863.html">魏其武安侯列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693853.html">韩长孺列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693843.html">李将军列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693833.html">匈奴列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693823.html">卫将军骠骑列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693811.html">平津侯主父列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693801.html">南越列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693791.html">东越列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693782.html">朝鲜列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693773.html">西南夷列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693763.html">司马相如列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693752.html">淮南衡山列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693741.html">循吏列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693732.html">汲郑列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693722.html">儒林列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693712.html">酷吏列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693702.html">大宛列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693691.html">游侠列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693682.html">佞幸列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693672.html">滑稽列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693662.html">日者列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693653.html">龟策列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693642.html">货殖列传</a></li>
              <li><a href="http://www.uaut.cn/shiji/1655693632.html">太史公自序</a></li>
            </ul>
        </div>
      </div>
    </div>
    <div class="col-7">
      <RouterView />
    </div>
  </div>



  </div>

</template>

<style scoped>
.scw-catalogue ul{
  
}
.scw-catalogue li{
  font-size: 1.2rem;
  line-height: 36px;
  display: inline-block;
  min-width: 8rem;
  margin-right: 1rem;
}


</style>
