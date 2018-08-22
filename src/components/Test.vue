<template>
  <div id="didi-navigator">
    <ul>
      <!--<li v-for="tab in tabs" :value="tab.t" :key="tab.x">-->
        <li v-for="tab in tabs" :value="tab.text" :key="tab.text">
          {{tab.text}}
        </li>
    </ul>
</div>
</template>

<script>
  export default {
    Test: "/Test",
    data() {
      return {
        tabs: [{
            text: "巴士"
          },
          {
            text: "快车"
          },
          {
            text: "专车"
          },
          {
            text: "顺风车"
          },
          {
            text: "出租车"
          },
          {
            text: "代驾"
          }
        ]
      };
    }
  };

</script>
