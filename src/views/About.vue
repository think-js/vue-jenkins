<template>
  <div class="about">
    <h1>This is an about page</h1>
    <Hello msg="hi"/>
  </div>
</template>

<script lang="ts">

import { Component, Vue } from 'vue-property-decorator';
import Hello from '@/components/Hello.vue'; // @ is an alias to /src

@Component({
  components: {
    Hello,
  },
})
export default class About extends Vue {}
</script>
