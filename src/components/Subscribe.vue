<template>
  <section
    id="subscribe"
    class="relative my-32 bg-gradient-to-b from-primary-200/30 to-primary-100/10 pb-32 rounded-lg"
  >
    <div class="p-10">
      <h2 class="text-6xl font-bold text-white mb-6">Subscribe</h2>
      <p class="text-lg text-white">
        Subscribe to our newsletters and stay updated !
      </p>
      <form class="mt-12">
        <div class="h-20 w-1/2 flex items-center">
          <input
            class="h-full flex-grow rounded-l-lg px-10 text-lg"
            type="text"
            placeholder="Enter your email address"
          />
          <button
            class="h-full px-6 uppercase text-white font-bold bg-secondary rounded-r-md"
          >
            Subscribe
          </button>
        </div>
      </form>
    </div>
    <div class="absolute right-10 bottom-10 w-1/3">
      <img src="../assets/images/about-img.webp" alt="" />
    </div>
  </section>
</template>

<script>
export default {
  name: "SubscribeSection",
};
</script>

<style></style>
