<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lqjrtpm_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:snipd" {...props}></Icon>
<style>
:global(.lqjrtpm_b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.9 33.1c-6.6-6.6-6.6-17.2 0-23.7s17.2-6.6 23.7 0zM33.1 15c6.6 6.6 6.6 17.2 0 23.7s-17.2 6.6-23.7 0z");
}

</style>
