<template>
  <div>
    <h1 class="current-time">The current date/time is {{ currentTime }}.</h1>
    <h2>ahsdf</h2>
  </div>
</template>

<script>
    import moment from "moment";

    export default {
        computed: {
            currentTime() {
                debugger
                return moment().format("dddd, MMMM Do YYYY, h:mm:ss a");
            }
        }
    }
</script>

<style>
    .current-time {
        color: blue;
    }

</style>