<template>
  <div class="box-review box-review-3">
    <div class="header-part">
      <img src="../assets/images/image-irene.jpg" />
      <div class="name">
        <h1>Anne Wallace</h1>
        <span>Verified Buyer</span>
      </div>
    </div>
    <p class="box-review-text">
      "Put an order with this company and can only praise them for the very high
      standard. Will definitely use them again and recommend them to everyone "
    </p>
  </div>
</template>

<script>
export default {
  mounted() {
    const screenWidth = window.innerWidth;
    console.log(`Screen width: ${screenWidth}px`);
  },
};
</script>
