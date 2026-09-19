<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pwa4pmb-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:squircle-ide" {...props}></Icon>
<style>
:global(.pwa4pmb-z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.861 17.639L3.5 24L24 44.5l6.361-6.361m7.778-7.778L44.5 24L24 3.5l-6.361 6.361");
}

</style>
