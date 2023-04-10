<template>
<div>
  <div class="main-list">
      <h2>{{ item.name }}</h2>
      <p>{{ item.description }}</p>
  </div>
</div>
</template>
<script>
export default  {
  name: 'MainBlock',
  data() {
    return {
        items: [
          {
            id: 1,
            name: 'Сегодня прекрасный день!',
            description: 'описание новостей',
          },
          {
            id: 2,
            name: 'Сегодня прекрасный день!',
            description: 'описание новостей',
          },
          {
            id: 3,
            name: 'Сегодня прекрасный день!',
            description: 'описание новостей',
          },
        ]
    };
  }
}
</script>
<style lang="scss">
.news-list {
    > div {
      h2 {
        color: red;
      
      }
      p {
        color: green;
      }
    }
}
</style>