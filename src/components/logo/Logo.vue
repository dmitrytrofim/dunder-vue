<template>
  <img class="logo" :src="logoSrc" alt="" />
</template>

<script lang="ts" setup>
import logoSrc from '@/assets/images/svg/logo.svg'
</script>

<style scoped>
.logo {
  width: 400px;
  border: 1px solid #000;
}
</style>
