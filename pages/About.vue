<template>
  <section class="hero is-info is-bold">
    <div class="hero-body">
      <h1 class="title is-size-2">
        About
      </h1>
      <h2 class="subtitle is-size-4">
        わたしたちについて
      </h2>
    </div>

<div class="columns">
  <div class="column">
    First column
  </div>
  <div class="column">
    Second column
  </div>
  <div class="column">
    Third column
  </div>
  <div class="column">
    Fourth column
  </div>
</div>

  </section>
</template>

<script>
export default {
  fetch ({store}) {
    store.commit('resetMenu')
  }
}
</script>