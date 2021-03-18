<template>
  <div class="container">
    <div>
      <img class="mx-auto" src="~assets/cloudflare.svg" alt="Cloudflare Pages" width="350">
      <h1 class="title text-3xl mt-4">
        Deploy your Jamstack Website with <a href="https://pages.cloudflare.com/"> Cloudflare Pages.</a>
      </h1>
    </div>
    <div class="mt-8 text-lg">
      <a class="bg-orange-500 font-bold text-white rounded py-2 px-6 hover:bg-orange-600" href="https://pages.cloudflare.com/">
        Learn More
      </a>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/

.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
   -apple-system, system-ui, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Fira Sans", "Droid Sans", "Helvetica Neue", sans-serif;
  font-weight: 400;
  color: hsl(0, 30%, 10%);
  letter-spacing: 1px;
}
</style>
