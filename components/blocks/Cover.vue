<template>
  <section class="cover">
    <h1 class="cover__title">#РАКЛЕЧИТСЯ</h1>
    <button class="cover__arrow"></button>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.cover {
  width: 100%;
  min-height: 689px;
  display: flex;
  flex-direction: column;
  background-color: #613a93;
  /* position: relative; */
  align-items: center;
}

.cover__title {
  font-style: normal;
  font-weight: 800;
  font-size: 92px;
  line-height: 111px;
  text-align: center;
  color: #ffffff;
  margin: 290px auto 0px;
  text-transform: uppercase;
}

.cover__arrow {
  border: none;
  outline: none;
  min-width: 36px;
  min-height: 12px;
  background-color: inherit;
  background-image: url("data:image/svg+xml,%3Csvg width='38' height='15' viewBox='0 0 38 15' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M37 1L19 13L1 1' stroke='white' stroke-width='2'/%3E%3C/svg%3E%0A");
  background-position: center;
  background-size: cover;
  margin: 237px auto 0px;
}

.cover__arrow {
  cursor: pointer;
}
</style>
