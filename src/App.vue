<template>
  <div id="app">
    <header class="header">
      <h3 style="display: inline">嘉和系统运行监控</h3>
      <ul class="a-access"></ul>
    </header>
    <!--主体-->
    <div class="main clearfix">
      <div class="main-left" style="height: 90vh">
        <div class="border-container" style="height:22vh">
          <span class="top-left border-span"></span>
          <span class="top-right border-span"></span>
          <span class="bottom-left border-span"></span>
          <span class="bottom-right border-span"></span>
        </div>
        <div class="border-container" style="height: 30vh">
          <span class="top-left border-span"></span>
          <span class="top-right border-span"></span>
          <span class="bottom-left border-span"></span>
          <span class="bottom-right border-span"></span>
        </div>
        <div class="border-container" style="height: 30vh">
          <span class="top-left border-span"></span>
          <span class="top-right border-span"></span>
          <span class="bottom-left border-span"></span>
          <span class="bottom-right border-span"></span>
        </div>
      </div>
      <div class="main-middle" style="height: 90vh">
        <div class="border-container" style="height: 45vh">
          <span class="top-left border-span"></span>
          <span class="top-right border-span"></span>
          <span class="bottom-left border-span"></span>
          <span class="bottom-right border-span"></span>
        </div>
        <div class="border-container" style="height: 39vh">
          <div id="changedetail"></div>
          <span class="top-left border-span"></span>
          <span class="top-right border-span"></span>
          <span class="bottom-left border-span"></span>
          <span class="bottom-right border-span"></span>
        </div>
      </div>
      <div class="main-right" style="height: 90vh">
        <div class="border-container" style="height: 29vh">
          <span class="top-left border-span"></span>
          <span class="top-right border-span"></span>
          <span class="bottom-left border-span"></span>
          <span class="bottom-right border-span"></span>
        </div>
        <div class="border-container" style="height: 29vh">
          <span class="top-left border-span"></span>
          <span class="top-right border-span"></span>
          <span class="bottom-left border-span"></span>
          <span class="bottom-right border-span"></span>
        </div>
        <div class="border-container" style="height: 24vh">
          <span class="top-left border-span"></span>
          <span class="top-right border-span"></span>
          <span class="bottom-left border-span"></span>
          <span class="bottom-right border-span"></span>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Hippmonitor",
  data() {
    return {};
  },
  computed: {},
  components: {},
  mounted() {},
  methods: {}
};
</script>
<style>
@import "./assets/css/bootstrap.css";
@import "./assets/css/template2.css";
</style>
