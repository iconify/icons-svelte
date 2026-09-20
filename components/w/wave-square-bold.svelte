<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="aakbijbev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:wave-square-bold" {...props}></Icon>
<style>
:global(.aakbijbev) {
  fill: currentColor;
  d: path("M244 128v56a12 12 0 0 1-12 12H128a12 12 0 0 1-12-12V84H36v44a12 12 0 0 1-24 0V72a12 12 0 0 1 12-12h104a12 12 0 0 1 12 12v100h80v-44a12 12 0 0 1 24 0");
}

</style>
