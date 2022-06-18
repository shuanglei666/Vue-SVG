<template>
  <div class="home">
    home页
    <div class="box">
      <svg aria-hidden="true" class="svgClass">
        <!-- <use :xlink:href="iconName"  /> -->
        <use xlink:href="#icon-water"></use>
        <!-- 注意使用:<use xlink:href="#icon-XXX"></use>  XXX代表下载好的svg名称,修改之后就是<use xlink:href="#icon-water"></use>-->
      </svg>
    </div>
  </div>
</template>

<style scoped>
.svgClass{
  color: rgba(240, 20, 130, 0.8);
}

.svgClass:hover{
  fill: currentColor;
  color: pink;
}
</style>






