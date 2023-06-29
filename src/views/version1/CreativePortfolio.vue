<template>
  <div class="home-four">
    <Header />
    <Slider />
    <div class="shane_tm_section" id="about">
      <div class="shane_tm_about">
        <div class="container">
          <About />
        </div>
      </div>
    </div>
    <div class="shane_tm_section" id="portfolio">
      <div class="shane_tm_portfolio">
        <Portfolio />
      </div>
    </div>
  </div>
</template>

<script>
import Header from "../../components/Header";
import Slider from "../../components/slider/Slider";
import About from "../../components/about/About";
export default {
  components: {
    Header,
    Slider,
    About,
  },
};
</script>

<style lang="scss" scoped></style>
