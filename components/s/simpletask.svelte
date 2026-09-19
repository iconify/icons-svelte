<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ppq7xyhiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:simpletask" {...props}></Icon>
<style>
:global(.ppq7xyhiz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 13L19.13 37.47a2.23 2.23 0 0 1-3.17 0L4.5 26.08");
}

</style>
