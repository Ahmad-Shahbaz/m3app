<template>
  <v-data-table
    :headers='headers'
    :items='items'
  >
  </v-data-table>
</template>

<script>
const HEADERS = [
  { text: 'Date (dd/mm/yyyy h:m)', value: 'date' },
  { text: 'Guest ID', value: 'guestID' },
  { text: 'Device', value: 'device' },
  { text: 'Device ID', value: 'deviceID' },
  { text: 'Event', value: 'event' },
];

export default {
  name: 'datatable',
  data: () => ({
    headers: HEADERS,
    items: [],
  }),
};
</script>

<style>

</style>
