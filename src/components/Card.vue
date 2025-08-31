<template>
  <div class="mt-14 flex flex-col">
    <div class="relative">
      <img src="../assets/images/image-waffle-desktop.jpg" class="rounded object-cover" />
      <button
        class="text-nowrap md:w-[80%] md:left-[10%] left-1/4 w-[50%]
        absolute  -mt-5 cursor-pointer border flex justify-center items-center
        font-semibold hover:border-[#C83B0E] hover:text-[#C83B0E]
        rounded-3xl px-3 py-2 bg-white"
      >
        <img src="../assets/images/icon-add-to-cart.svg" alt="Cart" />
        Add to Cart
      </button>
    </div>
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
