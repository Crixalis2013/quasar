<template>
  <div class="q-pa-md">
    <q-btn color="purple" @click="showNotif" label="Show Notification" />
  </div>
</template>

<script>
export default {
  methods: {
    showNotif () {
      this.$q.notify({
        message: 'Jim pinged you.',
        icon: 'announcement'
      })
    }
  }
}
</script>
