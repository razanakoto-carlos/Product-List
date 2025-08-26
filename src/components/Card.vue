<template>
  <div class="mt-14 flex flex-col relative">
    <img src="../assets/images/image-waffle-desktop.jpg" class="rounded object-cover" />
    <button class="cursor-pointer gap-2 flex items-center transform justify-center border font-semibold hover:border-[#C83B0E] hover:text-[#C83B0E] rounded-3xl w-[50%] px-3 py-2 mx-auto absolute top-[65%] translate-x-1/2 bg-white">
      <img src="../assets/images/icon-add-to-cart.svg" alt="Cart">
      Add to Cart</button>
    <h3 class="mt-7 text-gray-500">Waffle</h3>
    <p class="my-2 font-semibold text-lg">Waffle with berries</p>
    <span class="text-[#C83B0E] font-semibold text-lg">$6.50</span>
  </div>
</template>
<script>
export default {
  name: 'Card',
  data() {
    return {}
  },
}
</script>
