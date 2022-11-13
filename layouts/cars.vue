<template>
  <NuxtLink to="/">KMC</NuxtLink>
  <!--  output the page content-->
  <div>
    <slot/>
  </div>

  <footer>
    <ul>
      <li>
        <NuxtLink to="/">Home</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/about">About</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/cars">Cars</NuxtLink>
      </li>
    </ul>
  </footer>

</template>

<style scoped>
.router-link-exact-active {
  color: #12b488;
}
</style>