<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="puruqy1ne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:trading-212" {...props}></Icon>
<style>
:global(.puruqy1ne) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30 8.254l13.5 31.492H32.247L24 21.754l-8.247 17.992H4.5L18 8.254z");
}

</style>
