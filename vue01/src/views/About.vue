<template>
  <div class="about">
    <h1>This is an about page</h1>
    <div>
    <input type="text" v-model = aaa>
    <div>
      {{aaa}}
    </div>
</div>
  </div>
</template>

<script>
export default {
    data () {
        return{
            aaa: "123456"
        }
    }
}
</script>
