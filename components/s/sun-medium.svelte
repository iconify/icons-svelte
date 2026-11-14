<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_m_psi6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:sun-medium" {...props}></Icon>
<style>
:global(.o_m_psi6t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 12a5 5 0 1 0 10 0a5 5 0 1 0-10 0Zm5-9.75v2m0 15.5v2M2.25 12h2m15.5 0h2M6.5 6.5L5 5m12.5 1.5L19 5M6.5 17.5L5 19m12.5-1.5L19 19");
}

</style>
