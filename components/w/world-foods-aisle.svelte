<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pz7n1-xsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:world-foods-aisle" {...props}></Icon>
<style>
:global(.pz7n1-xsw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11h18a9 9 0 0 1-18 0m6 0l8.5-8M13 11l8.5-6.5");
}

</style>
