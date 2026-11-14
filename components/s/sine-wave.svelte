<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ucs_frbtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sine-wave" {...props}></Icon>
<style>
:global(.ucs_frbtp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12h19m-18 0c2.5-8.5 6-8.5 8.5 0s6 8.5 8.5 0");
}

</style>
