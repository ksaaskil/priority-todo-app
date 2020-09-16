<template>
  <div class="text-h3">
    TODO
  </div>
</template>
<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";

@Component
export default class TodoList extends Vue {
  @Prop() private msg!: string;
}
</script>
<style scoped lang="scss">
.hello {
  font-size: 2rem;
}
</style>
