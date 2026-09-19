<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yf4bm3csm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:sd-worx" {...props}></Icon>
<style>
:global(.yf4bm3csm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.644 4.5l-6.547 31.05m-8.511 7.95l2.993-26.935M12.356 24.14l1.871 11.036");
}

</style>
