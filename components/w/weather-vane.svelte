<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pv7jcmbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:weather-vane" {...props}></Icon>
<style>
:global(.pv7jcmbmq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 6h17.5m-3.25-3.25L20.5 6l-3.25 3.25M3 2.75L6.25 6L3 9.25M12 6v15.5M7 15h10");
}

</style>
