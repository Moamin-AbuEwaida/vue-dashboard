<template>
  <section id="category" class="flex flex-col items-center py-32">
    <h2 class="my-10 text-6xl font-bold text-white">Category</h2>
    <div class="grid grid-cols-3 place-items-center">
      <div
        v-for="category of categories"
        :key="category.title"
        class="text-white grid place-items-center gap-5 text-center"
      >
        <div class="p-10">
          <img :src="category.image" alt="" class="w-full" />
        </div>
        <h3 class="text-3xl font-bold">{{ category.title }}</h3>
        <p class="w-3/4">
          {{ category.desc }}
        </p>
      </div>
    </div>
  </section>
  <section
    class="grid grid-flow-col grid-cols-2 gap-10 text-white items-center"
  >
    <div class="p-10">
      <img src="../assets/images/category2-img.webp" alt="" />
    </div>
    <div>
      <div>
        <h2 class="text-6xl font-bold">What's that</h2>
        <div class="flex items-center gap-5">
          <h2 class="text-6xl font-bold">Halloween</h2>
          <img src="../assets/images/head2-img.png" alt="" />
        </div>
      </div>
      <p class="mt-12 text-xl w-2/3">
        Halloween or Hallowe'en, also known as Allhalloween, All Hallows' Eve,
        or All Saints' Eve, is a celebration observed in many countries on 31
        October, the eve of the Western Christian feast of All Hallows' Day.
      </p>
    </div>
  </section>
</template>

<script>
export default {
  name: "CatergorySection",
  data() {
    return {
      categories: [
        {
          title: "Ghost",
          image: category1,
          desc: "Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nihil magnam rem, illo illum corrupti quasi.",
        },
        {
          title: "Witch",
          image: category2,
          desc: "Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nihil magnam rem, illo illum corrupti quasi.",
        },
        {
          title: "Pumpkin",
          image: category3,
          desc: "Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nihil magnam rem, illo illum corrupti quasi.",
        },
      ],
    };
  },
};

import category1 from "../assets/images/category/category1-img.webp";
import category2 from "../assets/images/category/category2-imgC.webp";
import category3 from "../assets/images/category/category3-img.webp";
</script>

<style></style>
