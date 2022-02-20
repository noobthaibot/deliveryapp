<template>
  <div className="auth">
  <my-input label="Введите имя"
  placeholder="Введите имя"></my-input>
  </div>
</template>

<script>
import MyInput from "@/components/ui/MyInput";

export default {
  name: "AppAuth",
  components: {
    MyInput
  },
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
