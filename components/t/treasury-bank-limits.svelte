<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pmjl_mbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:treasury-bank-limits" {...props}></Icon>
<style>
:global(.pmjl_mbsh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21.5h19M3 21.5v-11h4v11m3 0V13h4v8.5m3 0V7.75h4V21.5M2.5 4.75H5m3 0h2.5m3 0H16m3 0h2.5");
}

</style>
