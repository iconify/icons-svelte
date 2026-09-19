<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ze0sg2bkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tunerly" {...props}></Icon>
<style>
:global(.ze0sg2bkk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 14.25V24A9.75 9.75 0 0 0 24 24a9.75 9.75 0 0 1 19.5 0v9.75");
}

</style>
