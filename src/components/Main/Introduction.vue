<template>
  <div class="introduction-box">
    <p class="hiMessage">Hi, my name is</p>
    <h1>MURAT ASLAN.</h1>
    <p class="presentation">
      I'm a full stack developer in Ankara.
    </p>
  </div>
</template>

<script>
export default {
  name: "Introduction"
};
</script>

<style scoped lang="scss">
.introduction-box {
  font-size: 2.4vw;
  @media (max-width: 900px) {
    font-size: 18px;
  }
  .hiMessage {
    color: var(--m-hi-message);
    @media (max-width: 900px) {
      text-align: center;
    }
  }
  h1 {
    width: 90%;
    background-image: linear-gradient(
      0deg,
      var(--m-heading-background-gradient-1),
      var(--m-heading-background-gradient-2)
    );
    background-size: 30px 30px;
    background-repeat: repeat-x;
    background-position: bottom;
    color: var(--m-murat-aslan);
    @media (max-width: 900px) {
      width: 85%;
      background-size: 14px 14px;
      text-align: center;
      margin-left: auto;
      margin-right: auto;
    }
    @media (max-width: 649px) {
      width: 85%;
      background-size: 14px 14px;
      text-align: center;
      margin-left: auto;
      margin-right: auto;
      font-size: 1.8rem;
      margin-top: 8px;
      margin-bottom: 10px;
    }
  }
  .presentation {
    line-height: 4.2rem;
    color: var(--m-presentation);
    @media (max-width: 900px) {
      text-align: center;
    }
    @media (max-width: 649px) {
      line-height: 2.2rem;
    }
  }
}
</style>
