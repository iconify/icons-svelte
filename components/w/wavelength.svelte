<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fc-s4n8pn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:wavelength" {...props}></Icon>
<style>
:global(.fc-s4n8pn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15c1.75-5 4.25-5 6 0s4.25 5 6 0s4.25-5 6 0m-15-9h12m-12-2v4m12-4v4");
}

</style>
