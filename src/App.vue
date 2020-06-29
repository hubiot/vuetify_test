<template>
  <v-app>
    <DatePicker></DatePicker>
  </v-app>
</template>

<script>
import DatePicker from "./components/DatePicker";

export default {
  name: "App",
  components :{
    DatePicker
  },
  data () {
    return {
      // date: new Date().toISOString().substr(0, 10),
      date: '',
      menu2: false,
    }
  }
}
</script>

