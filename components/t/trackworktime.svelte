<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zkxz_20sb"/><path class="i2h9-4bpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:trackworktime" {...props}></Icon>
<style>
:global(.i2h9-4bpt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.6 20.46a8.62 8.62 0 1 1-8.6 8.62a8.62 8.62 0 0 1 8.6-8.62m.1 8.62l-4.67 4.56m4.67-10.07v5.51");
}

:global(.zkxz_20sb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 20.43a2 2 0 0 0-2-2h-35a2 2 0 0 0-2 2v17.3a2 2 0 0 0 2 2h35a2 2 0 0 0 2-2ZM24 9.41a9 9 0 0 1 9 9H15a9 9 0 0 1 9-9");
}

</style>
