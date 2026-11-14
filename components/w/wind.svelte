<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jmq1ixbvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:wind" {...props}></Icon>
<style>
:global(.jmq1ixbvx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9H14a3 3 0 1 0-3-3m-8.5 7h16a2.75 2.75 0 1 1-2.75 2.75M2.5 17h7");
}

</style>
