<template>
  <div>
    <drawer
      width="200px;"
      :show.sync="drawerVisibility">

    <div slot="drawer">
      <!-- 菜单内容 -->
    </div>

    <!-- rourer-view 作为默认插槽内容 -->
    <div>
      <router-view></router-view>
    </div>

    </drawer>
  </div>
</template>
