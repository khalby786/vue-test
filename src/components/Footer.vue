<template>
  <footer>
    <a class="darkmode-ignore" href="//blog.khaleelgibran.com"
      ><span>blog</span></a
    >&nbsp;·&nbsp;
    <!-- <p class="darkmode-ignore" @click="toggle" id="theme">
      {{ theme }} theme (beta)
    </p> -->
    <a href="https://1mb.club/"><span>1mb club</span></a>
    <br />
    <!-- <a
      class="darkmode-ignore"
      href="//www.youtube.com/channel/UCXf1CMT59vnhMKi4nU0a9kQ"
      ><p>check out this cool youtube channel (not mine)</p></a
    > -->

    <p class="footer-text">
      <a href="https://github.com/khalby786/personal-website/issues">Report a problem</a> ~
      <a href="https://github.com/khalby786/personal-website">View source</a>
      <br />
      Powered by <a href="https://netlify.com">Netlify</a> ~
      Analytics by <a href="https://splitbee.io">Splitbee</a>
    </p>
  </footer>
</template>

<script>
export default {
  name: "Footer",
  data: function () {
    return {
      // theme: "light",
      // darkmode: new Darkmode(),
    };
  },
  // methods: {
  //   toggle: function () {
  //     this.darkmode.toggle();
  //     if (this.darkmode.isActivated() === true) {
  //       this.theme = "light";
  //     } else {
  //       this.theme = "dark";
  //     }
  //   },
  // },
  // mounted: function () {
  //   if (this.darkmode.isActivated() === true) {
  //     this.theme = "dark";
  //   } else {
  //     this.theme = "dark";
  //   }
  // },
};
</script>

<style scoped>
footer {
  text-align: center;
  margin-top: 100px;
  padding-top: 20px;
  border-top: 2px solid#DCDCDC;
}

#theme {
  cursor: pointer;
  color: #6b17e6;
  transition: opacity 0.2s;
  text-decoration: underline;
}

p {
  margin-bottom: 0px;
  margin-top: 0px;
}

.footer-text {
  text-align: center;
  font-size: 14px;
  padding-top: 10px;
  color: gray;
}

.footer-text > a {
  color: inherit;
  text-decoration: none;
}
</style>