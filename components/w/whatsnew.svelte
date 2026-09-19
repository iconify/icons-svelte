<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hqu_reb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:whatsnew" {...props}></Icon>
<style>
:global(.hqu_reb5t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 9.5v29m39-29v29m-7.8-29v29m-7.8-29v29m-7.8-29v29m-7.8-29v29");
}

</style>
