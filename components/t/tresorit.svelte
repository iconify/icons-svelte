<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jeom8nher"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tresorit" {...props}></Icon>
<style>
:global(.jeom8nher) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.75 34.25v-20.5L24 3.5L6.25 13.75v20.5L24 44.5zm-35.5-8.24L34.61 9.63");
}

</style>
