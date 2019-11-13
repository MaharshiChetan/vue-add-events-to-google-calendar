<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <AddToCalendar
      :buttonText="buttonText"
      :title="title"
      :startTime="startTime"
      :endTime="endTime"
      :location="location"
      :details="details"
    />
  </div>
</template>

<script>
import AddToCalendar from './components/AddToCalendar.vue'

export default {
  name: 'app',

  data() {
    return {
      buttonText: "Add to calendars",
      details: "this is testing of add to calendar component",
      endTime: new Date('11/22/2019 5:00 pm'),
      location: "ruby tower, dadar",
      startTime: new Date('11/25/2019 6:00 pm'),
      title: "Excellencia",
    }
  },

  components: {
    AddToCalendar
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
