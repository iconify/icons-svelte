<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smmtp_n-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:rowing" {...props}></Icon>
<style>
:global(.smmtp_n-r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12.5h18c-3.5 4-14.5 4-18 0Zm13-9l-7 14M2.5 20q2.25-1.5 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
