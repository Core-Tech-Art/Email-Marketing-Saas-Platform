<template>
  <div
    class="my-2  bg-white border rounded-xl bg-pricing-card-bg dark:bg-gray-800 dark:border-gray-700"
  >
    <div class="text-center mt-8">
      <p class="font-primary text-2xl font-bold text-card-subtitle">
        Verification Credits
      </p>
      <p class="font-primary text-xs text-primary">
        10,000 never expiring verification credits
      </p>
    </div>
    <div class="p-5 text-center">
      <p class="mb-5 text-sm font-primary font-semibold dark:text-white text-center">
        ONE TIME PRICE
      </p>
      <p class="text-5xl font-primary font-semibold mb-5">only $1999</p>
      <p class="text-[13.154px] text-[#64607D] font-bold font-primary mb-3">
        YOU CAN USE FOR
      </p>
      <p class="text-[14.35px] text-primary font-bold font-primary mb-3">
        - Email Checker
      </p>
      <p class="text-[14.35px] text-primary font-bold font-primary mb-3">
        - Email List Cleaning
      </p>
      <p class="text-[14.35px] text-primary font-bold font-primary mb-3">
        - Bulk Email Verification
      </p>
      <p class="text-[14.35px] text-primary font-bold font-primary mb-3">
        - ESP Integration Import
      </p>
      <p class="text-[14.35px] text-primary font-bold font-primary mb-3">
        - Email Verification API
      </p>
    </div>
    <div class="flex flex-row p-5 justify-between">
      <a
        class="text-sm text-primary font-primary flex items-center font-bold leading-10 cursor-pointer"
        >More Details
        <img src="../../assets/images/home/pricing/r-arrow.png" class="h-1/2"
      /></a>
      <button class="py-2 px-4 w-50 bg-[#2078BE] text-white rounded-full font-medium">
        BUY NOW
      </button>
    </div>
  </div>
</template>
<script>
export default {
  props: ["title", "content"],
};
</script>
