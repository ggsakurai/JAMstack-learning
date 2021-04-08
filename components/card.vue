<template>
  <article class="card">
    <h1 class="card_date">{{ event_date }}</h1>
    <h1 class="card_title">{{ title }}</h1>
    <h1 class="card_description">{{ description }}</h1>
    <p class="card_date">{{ date }}</p>
  </article>
</template>
<script>

export default {
  props: {
    event_date: {
      type: String,
      default: ''
    },
    title: {
      type: String,
      default: ''
    },
    description: {
      type: String,
      default: ''
    },
    id: {
      type: String,
      default: ''
    },
    date: {
      type: String,
      default: ''
    }
  }
}
</script>
