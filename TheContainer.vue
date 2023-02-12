<template>
  <div class="wrapper">
    <!-- 헤더 -->
    <Header />  
    <div class="content-view">
      <router-view></router-view>
    </div>
  </div>
</template>
<script>
import Header from '@/components/layout/Header' 
export default {
  components: {Header},
  name: "TheContainer"
}
</script>