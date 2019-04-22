<template>
  <div class="about">
    <h1>This is an about page</h1>
    <event-card></event-card>
  </div>
</template>

<script lang="ts">
  import { Vue, Component } from "vue-property-decorator";
  import EventCard from "@/components/event-card.vue";

  @Component({
    components: {
      EventCard
    }
  })
  export default class About extends Vue {}
</script>
