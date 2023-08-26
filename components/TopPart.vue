<template>
  <section class="top-part">
    <div class="left-part">
      <h1>10,000 of our users love our products</h1>
      <p>
        We only provide great products combined with excellent customer service.
        See what out satisfied customers are saying about our services.
      </p>
    </div>
    <div class="right-part">
      <div class="blocks block-1">
        <StarReview />
        <h1>Rated 5 Stars in Reviews</h1>
      </div>
      <div class="blocks block-2">
        <StarReview />
        <h1>Rated 5 Stars in Report Guru</h1>
      </div>
      <div class="blocks block-3">
        <StarReview />
        <h1>Rated 5 Stars in BestTech</h1>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "TopPart",
};
</script>

<style>
.top-part {
  /* display: grid;
  grid-template-columns: repeat(2, 1fr); */
  display: flex;
  justify-content: space-between;
  padding: 12rem 13rem 6rem 13rem !important;
}

.left-part h1 {
  font-size: 4.7rem;
  width: 30rem;
  color: hsl(300, 43%, 22%);
  font-weight: 700;
}

.left-part p {
  font-size: 1.5rem;
  color: hsl(303, 10%, 53%);
  line-height: 2.3rem;
  width: 38rem;
  font-weight: 500;
  margin-top: 2.2rem;
}

.blocks {
  display: flex;
  background-color: hsl(300, 24%, 96%);
  justify-content: space-around;
  width: 32rem;
  border-radius: 10px;
  padding: 1.5rem 0;
  font-size: 15px;
}

.blocks h1 {
  font-weight: 700;
  color: hsl(300, 43%, 22%);
}

.right-part {
  display: flex;
  flex-direction: column;
  gap: 1.4rem;
  margin-top: 2rem;
}

.block-2 {
  margin-left: 3.5rem;
}

.block-3 {
  margin-left: 6.8rem;
}

@media (max-width: 425px) {
  .top-part {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 100vh !important;
    width: 170vw !important;
  }

  .left-part {
    text-align: center;
  }

  .left-part h1 {
    width: 100% !important;
    text-align: center;
  }

  .left-part p {
    width: 35rem !important;
  }

  .right-part {
    gap: 0.7rem !important;
  }

  .blocks {
    padding: 2rem 0 !important;
  }

  .block-2,
  .block-3 {
    margin-left: 0 !important;
  }
}
</style>
