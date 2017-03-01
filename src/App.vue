<template id="main">
    <v-ons-page>
      <v-ons-toolbar>
        <div class="center">Onsen UI</div>
      </v-ons-toolbar>
      <div>Hello World!</div>
      <p style="text-align: center">
        <v-ons-button @click="alert">Click Me!</v-ons-button>
      </p>
    </v-ons-page>
</template>
<script>
    export default{
        methods: {
          alert() {
            this.$notification.alert('This is an Onsen UI alert notification test.');
          }
        }
    };
</script>
