<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="x5jgg-16g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:vector-two-fill" {...props}></Icon>
<style>
:global(.x5jgg-16g) {
  fill: currentColor;
  d: path("m229.66 197.66l-32 32A8 8 0 0 1 184 224v-24H80a8 8 0 0 1-8-8V80H48a8 8 0 0 1-5.66-13.66l32-32a8 8 0 0 1 11.32 0l32 32A8 8 0 0 1 112 80H88v104h96v-24a8 8 0 0 1 13.66-5.66l32 32a8 8 0 0 1 0 11.32");
}

</style>
