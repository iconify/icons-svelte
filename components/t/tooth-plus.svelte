<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ten1j2bdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:tooth-plus" {...props}></Icon>
<style>
:global(.ten1j2bdp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19.063 12.409C19.523 10.977 20 9.727 20 8c0-2.5-1-4.5-3.5-4.5c-2 0-3 1-4.5 1s-2.5-1-4.5-1C5 3.5 4 5.5 4 8s1 4 1.5 6.5l1 5c.25 1.25 1.75 1.25 2 0l1-4.5c.25-1 1.25-1.5 2.5-1.5s2.25.5 2.5 1.5l.046.208M18 15v6m-3-3h6");
}

</style>
