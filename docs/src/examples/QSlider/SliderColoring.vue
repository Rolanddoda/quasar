<template>
  <div class="q-pa-lg">
    <q-slider
      v-model="model"
      color="orange"
      thumb-color="purple"
      label-color="black"
      markers
      marker-labels
      switch-marker-labels-position
      label-always
      switch-label-position
      :min="0"
      :max="6"
    />
  </div>
</template>

<script>
import { ref } from 'vue'

export default {
  setup () {
    return {
      model: ref(2)
    }
  }
}
</script>
