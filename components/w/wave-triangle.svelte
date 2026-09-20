<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ekc-vbchj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:wave-triangle" {...props}></Icon>
<style>
:global(.ekc-vbchj) {
  fill: currentColor;
  d: path("m238.48 132.68l-52 72a8 8 0 0 1-13 0L76 69.66l-45.51 63a8 8 0 1 1-13-9.36l52-72a8 8 0 0 1 13 0l97.51 135l45.51-63a8 8 0 1 1 13 9.36Z");
}

</style>
