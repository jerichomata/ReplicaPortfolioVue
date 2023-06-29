<template>
  <div class="about_inner">
    <div class="left">
      <div class="image">
        <img src="../../assets/img/about.png" />
        <div
          class="main"
          v-scroll-reveal="{ delay: 20 }"
          :style="{ backgroundImage: 'url(' + aboutImg + ')' }"
        ></div>
      </div>
      <!-- End image  -->
    </div>
    <!-- End left -->

    <div class="right">
      <div class="shane_tm_title">
        <span v-scroll-reveal="{ delay: 20 }">About Me</span>
        <h3 v-scroll-reveal="{ delay: 40 }">
          Jericho Mata
        </h3>
        <h9>
              Software Engineer based in San Jose, CA
        </h9>
      </div>
      <div class="text" v-scroll-reveal="{ delay: 60 }">
        <p>
          I'm a UC Davis graduate with a reputation for constantly tackling new challenges and 
              having strong interpersonal skills from working with different teams.
              My passion for development started as a young elementary student
              as I was helping my mom organize our bills. We've always used pen and paper 
              but constantly lost track of our expenses so I learned Excel where I started using the basic 
              code editor.
              From there my interests in application development grew especially in creating
              tools teaching financial literacy.
        </p>
      </div>
      <div class="shane_tm_button" v-scroll-reveal="{ delay: 80 }">
        <a>
          Let's Chat
        </a>
      </div>
    </div>
    <!-- End right -->
  </div>
</template>

<script>
export default {
  data() {
    return {
      aboutImg: require("../../assets/img/about.png"),
    };
  },
};
</script>
