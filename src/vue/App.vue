<template>
  <div>
    <router-view></router-view>
  </div>
</template>

<script lang="ts">
import { Vue, Component } from "vue-property-decorator"
@Component
export default class HelloWorld extends Vue {
}
</script>