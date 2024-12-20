<template>
  <div class="hello">
    <a-card>
      <a-button type="primary">
        按钮按钮
      </a-button>
      <a-button v-if="name=='sdf'" type="primary">
        按钮按钮
      </a-button>
    </a-card>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  components: {},

  data() {
    return {
      name: 'hello world',
      num: 0,
      show: false
    }
  },

  watch: {},
  methods: {
    getData(){
      let a = 1
    }
  }
}
</script>

<style scoped></style>
