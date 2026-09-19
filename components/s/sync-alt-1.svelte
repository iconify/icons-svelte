<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ggu20w3ko"/><path class="by6ip63pp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:sync-alt-1" {...props}></Icon>
<style>
:global(.by6ip63pp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.58 42.133l12.839-16.52a1 1 0 0 0-.79-1.613h-25.7a.95.95 0 0 0-.75 1.534l12.9 16.599a.95.95 0 0 0 1.501 0");
}

:global(.ggu20w3ko) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.42 5.867l-12.839 16.52a1 1 0 0 0 .79 1.613h25.7a.95.95 0 0 0 .75-1.534l-12.9-16.599a.95.95 0 0 0-1.501 0");
}

</style>
