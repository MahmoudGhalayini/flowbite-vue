<template>
  <div class="vp-raw">
    <fwb-range v-model.number="value" />
    <pre>Selected value: {{ value }}</pre>
  </div>
</template>

<script lang="ts" setup>
import { ref } from 'vue'

import { FwbRange } from '../../../../src/index'

const value = ref(10)
</script>
