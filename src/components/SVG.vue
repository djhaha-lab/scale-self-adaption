<script setup>
import { SVG } from "@svgdotjs/svg.js";
var draw = SVG().addTo("body").size(300, 300);
var rect = draw.rect(100, 100).attr({ fill: "#f06" });
</script>

<template>
  <div class="bg-black"></div>
</template>

<style scoped></style>
