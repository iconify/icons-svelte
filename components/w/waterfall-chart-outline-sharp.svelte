<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1isrostl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:waterfall-chart-outline-sharp" {...props}></Icon>
<style>
:global(.g1isrostl) {
  fill: currentColor;
  d: path("M3 20v-6h3v6zm5-6V9h3v5zm5-5V4h3v5zm5 11V4h3v16z");
}

</style>
