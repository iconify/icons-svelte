<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g9fwcubtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:staggered-junction" {...props}></Icon>
<style>
:global(.g9fwcubtn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5H9V2.5M2.5 10H9v11.5m6-19V14h6.5m0 5H15v2.5");
}

</style>
