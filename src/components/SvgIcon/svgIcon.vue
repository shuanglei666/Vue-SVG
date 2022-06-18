<template>
  <div class="svgIcon">
    svgIcon页
    <svg aria-hidden="true" class="svgClass">
      <!-- <use :xlink:href="iconName" /> -->
      <use xlink:href="#icon-water"></use>
    </svg>
  </div>
</template>

<style scoped>
.svgClass {
  color: pink;
}
.svgClass:hover {
  color: #409eff;
}
</style>