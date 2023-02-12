<script setup lang="ts">

import { sum } from 'vite-vanilla-ts-lib-starter-core'

const test = ref(sum(1, 4))

const test2 = ref('foo')
</script>

<template>
  Test : {{ test }}
</template>
