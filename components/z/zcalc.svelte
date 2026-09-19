<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cp3y-xb3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:zcalc" {...props}></Icon>
<style>
:global(.cp3y-xb3k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4M11.316 30.91h10.992m5.298 1.996h9.078m-9.178-4h9.078M12.272 15.8h9.08m-4.54 9.584v11.053m11.156-24.874l8.154 8.43m0-8.43l-8.154 8.43");
}

</style>
