<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y9ohltbnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tiktok" {...props}></Icon>
<style>
:global(.y9ohltbnz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.73 22.4A10.55 10.55 0 1 0 29.27 33V4.5a10.55 10.55 0 0 0 10.55 10.55");
}

</style>
