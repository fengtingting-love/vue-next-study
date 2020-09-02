<template>
  <div id="counter">
    Counter: {{counter}}
  </div>
</template>

<script lang="ts">
    import {Vue} from 'vue-class-component';

    const Counter = {
        data() {
            return {
                counter:0,
            }
        }
    };

    export default class Home extends Vue {

    }
</script>
