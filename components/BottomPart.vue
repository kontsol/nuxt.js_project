<template>
  <section class="bottom-part">
    <BoxReview_1 />
    <BoxReview_2 />
    <BoxReview_3 />
  </section>
</template>

<script>
export default {
  name: "BottomPart",
};
</script>

<style>
.bottom-part {
  padding: 0 13rem 10rem 13rem !important;
  display: flex;
  justify-content: center;
  gap: 1.8rem;
}

.box-review {
  background-color: hsl(300, 43%, 22%);
  padding: 3rem 2rem;
  border-radius: 12px;
  height: 19.5rem;
  width: 30rem;
}

.header-part {
  display: flex;
  gap: 1rem;
  margin-bottom: 2.1rem;
}

.header-part img {
  width: 3rem;
  border-radius: 50%;
}

.header-part h1 {
  color: hsl(0, 0%, 100%);
  font-weight: 500;
  font-size: 1.2rem;
  margin-bottom: 0.25rem;
}

.header-part span {
  color: hsl(333, 80%, 67%);
  font-weight: 700;
  font-size: 1.3rem;
}

.box-review-text {
  color: hsl(0, 0%, 100%);
  font-weight: 400;
  font-size: 1.4rem;
  line-height: 1.7rem;
}

.box-review-2 {
  margin-top: 2rem;
}

.box-review-3 {
  margin-top: 4rem;
}

@media (max-width: 425px) {
  .bottom-part {
    padding: 5rem 6.5rem !important;
    flex-direction: column;
    gap: 1.2rem !important;
  }

  .box-review {
    width: 32rem !important;
    height: 20rem !important;
  }

  .box-review-2,
  .box-review-3 {
    margin-top: 0 !important;
  }
}
</style>
