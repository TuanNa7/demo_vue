<template>
  <div class="search-area">
    <h4>ご希望の勤務地を選択して下さい。（複数選択可）</h4>
    <div class="search_list">
      <label>
        <input type="checkbox" name="check_list_search">
        &nbsp;
        大阪市北区&nbsp;
        <span>(4)</span>
      </label>
    </div>
    <button class="btn-submit">この条件で検索する</button>
  </div>
</template>
<style>
  .search-area{
    width: 100%;
    box-sizing: border-box;
    margin: 0 auto 20px;
    padding: 5px 5px 20px;
    background: #fff;
    border: 3px solid #ded6c9;
  }
  .search-area > h4{
    padding: 5px;
    margin-bottom: 15px;
    background: #f9f4f0;
    text-align: left;
    font-weight: normal;
    font-size: 14px;
  }
  .search_list{
    margin: 0 10px;
    color: #5895d8;
  }
  .search_list > label > span{
    color: #ff0000;
  }
  .btn-submit{
    width: 202px;
    position: relative;
    left: 50%;
    margin-left: -101px;
    border: none;
    box-sizing: border-box;
    cursor: pointer;
    padding: 6px 20px;
    background: #e74291;
    border-radius: 5px;
    color: #fff;
    font-size: 18px;
  }
</style>