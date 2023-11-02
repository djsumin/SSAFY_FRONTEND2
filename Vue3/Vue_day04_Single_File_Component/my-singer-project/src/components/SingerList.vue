<template>
    <div class="singer-list-title">
        <h2>가수 목록</h2>
        <SingerDetail/>
    </div>
</template>

<script setup>
import SingerDetail from './singer/SingerDetail.vue';

</script>

<style scoped>
.singer-list-title{
    text-align: center;
}
</style>