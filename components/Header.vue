<template>
  <div class="header">
    <div class="content-header" >
      <nuxt-link to="/">
        <img src="https://www.toremasse-trial.com/assets/img/upload/1583800512_2a6f4a9d00d26b8dbc9e567ec3d65f87.png?1583800512" />
      </nuxt-link>
    </div>
  </div>
</template>
<style>
  .header{
    width: 100%;
    height: 76px;
    padding: 10px;
    clear: both;
    z-index: 9999;
    background: #fff;
    border-bottom: 1px solid #e6e6e6;
    box-sizing: border-box;
  }
  .content-header{
    margin: 0 auto;
    width: 980px;
    height: 100%;
    position: relative;
    z-index: 200;
    overflow: hidden;
  }
  .header img{
    width: 230px;
    height: 55px;
  }
</style>