<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rk_8lkbiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:skysafari" {...props}></Icon>
<style>
:global(.rk_8lkbiv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.85 3.41A21.49 21.49 0 0 1 8.05 38.5a21.5 21.5 0 1 0 21.8-35.09");
}

</style>
