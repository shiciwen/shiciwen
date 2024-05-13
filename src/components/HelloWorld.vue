<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="">
    <div class="row subject bg-secondary-subtle">
      <h5>热门经典</h5>
      <ul class="list-inline">
        <li class="list-inline-item"><RouterLink to="/">史记</RouterLink></li>
        <li class="list-inline-item">漢</li>
        <li class="list-inline-item">魏晉</li>
        <li class="list-inline-item">南北朝</li>
        <li class="list-inline-item">唐</li>
        <li class="list-inline-item">五代十國</li>
      </ul>
    </div>
    <div class="row subject bg-secondary-subtle">
      <h5>朝代</h5>
      <ul class="list-inline">
        <li class="list-inline-item"><RouterLink to="/">Home先秦</RouterLink></li>
        <li class="list-inline-item">漢</li>
        <li class="list-inline-item">魏晉</li>
        <li class="list-inline-item">南北朝</li>
        <li class="list-inline-item">唐</li>
        <li class="list-inline-item">五代十國</li>
      </ul>
    </div>
    <div class="row subject bg-secondary-subtle">
      <h5>体裁</h5>
      <ul class="list-inline">
        <li class="list-inline-item"><RouterLink to="/about">about诗经</RouterLink></li>
        <li class="list-inline-item">楚辞</li>
        <li class="list-inline-item">诗</li>
        <li class="list-inline-item">词</li>
      </ul>
    </div>
    <div class="row subject bg-secondary-subtle">
      <h5>作者／出处</h5>
      <ul class="list-inline">
        <li class="list-inline-item">古诗十九首</li>
        <li class="list-inline-item">司马相如</li>
        <li class="list-inline-item">司空图</li>
        <li class="list-inline-item">刘禹锡</li>
        <li class="list-inline-item">《论语》</li>
      </ul>
    </div>
  </div>
</template>




<style scoped>
.subject{
  margin-bottom: 20px;
}
</style>
