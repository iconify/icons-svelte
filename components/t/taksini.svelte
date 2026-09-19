<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y86rq3bow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:taksini" {...props}></Icon>
<style>
:global(.y86rq3bow) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.1 12.3h-7.8V4.5h23.4v7.8h-7.8v23.4H12.3v7.795h7.8z");
}

</style>
