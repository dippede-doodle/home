<script setup lang="ts">
import { useData } from 'vitepress'

// https://vitepress.dev/reference/runtime-api#usedata
const { site, frontmatter } = useData()
</script>

<template>
  <div style="position: relative; top: 0; left: 0; display: flex; margin: 0; padding:0; min-width: 96vw; min-height: 96vh; align-items: center; justify-content: center;">
    <div style="text-align: center; max-width: 60ch;">
      <Content />
    </div>
  </div>
</template>
