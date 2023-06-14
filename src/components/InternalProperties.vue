<template>
  <div>
    <div>InternalProperties<button @click="clickHandler">Click</button></div>
    <div>:D</div>
    <div ref="divacio"></div>
  </div>
</template>

<script>
export default {
  name: "InternalProperties",
  props: {
    name: String,
    propiedadquenoestaenprops: String,
  },
  data() {
    return {
        array: [1,2,3]
    }
  },
  methods: {
    clickHandler() {
      //console.log(this);
      const div = this.$refs.divacio;
      div.innerHTML = "hola";
      //console.log("clickHandler");
    },
  },
};
</script>