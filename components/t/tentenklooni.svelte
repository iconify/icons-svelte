<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l5gg833kf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tentenklooni" {...props}></Icon>
<style>
:global(.l5gg833kf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 4.5l17.92 9.75v19.5L24 43.5L6.08 33.75v-19.5ZM6.08 14.25L24 24m17.92-9.75L24 24m0 19.5V24");
}

</style>
