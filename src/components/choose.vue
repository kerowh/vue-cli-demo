<template>
    <div class="choose">
      <ul>
        <li>
          <router-link :to="{name:'HelloWorld',params:{worldmsg:'你好世界'}}">HelloWorld</router-link>
        </li>
        <li>
          <router-link :to="{name:'HelloEarth',params:{earthmsg:'你好地球'}}">HelloEarth</router-link>
        </li>
      </ul>
    </div>
</template>

<script>
export default {
  name: 'choose',
  worldmsg: '',
  earthmsg: ''
}
</script>

<style scoped>

</style>
