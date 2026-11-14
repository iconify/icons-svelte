<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1rezs9ee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:rugby-sevens" {...props}></Icon>
<style>
:global(.m1rezs9ee) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13.5a11 11 0 0 1 11-11a11 11 0 0 1-11 11M13 13h8l-5 8.5m-9.5-12l3-3");
}

</style>
