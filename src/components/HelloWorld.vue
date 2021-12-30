<template>
  <vwc-button layout="filled">Button</vwc-button>

  <vwc-circular-progress progress="0.7" density="0"></vwc-circular-progress>

  <vwc-icon type="home"></vwc-icon>

  <vwc-switch></vwc-switch>

  <vwc-icon-button icon="bin"></vwc-icon-button>

  <vwc-card
    label="Icon"
    heading="Icon Example"
    header-icon="chat-line"
    subtitle="Subtitle"
    supporting-text="Supporting Text"
  >
    <div>Using the icon attribute</div>
  </vwc-card>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
