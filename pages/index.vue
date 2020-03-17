<template>
  <div class="wrapper-page">
    <Header />
    <div class="wrapper-content">
      <p class="coppy-ichiran">株式会社採用戦略研究所のトレマッセ-TRIALのデモサイトになります。</p>
      <SearchArea />
      <ToTop />
    </div>
  </div>
</template>

<script>
// import Logo from '~/components/Logo.vue'
import Header from '~/components/Header.vue'
import  SearchArea from '~/components/SearchArea.vue'
import ToTop from '~/components/ToTop.vue'

export default {
  components: {
    Header, SearchArea, ToTop
  }
}
</script>

<style>
  .wrapper-page{
    background-image: url(https://www.toremasse-trial.com/template01/img/common/bg_list.png);
    min-height: 100vh;
  }
  .wrapper-content{
    text-align: left;
    width: 980px;
    margin: 30px auto 30px;
  }
  .coppy-ichiran{
    color: #0285BB;
    font-size: 18px;
    line-height: 24px;
    margin: 35px 10px;
    font-weight: bold;
  }
</style>
