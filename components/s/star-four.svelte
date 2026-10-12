<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="efsba9b2h"/><path class="to8m3ibcr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:star-four" {...props}></Icon>
<style>
:global(.efsba9b2h) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75q1.11 8.14 9.25 9.25q-8.14 1.11-9.25 9.25q-1.11-8.14-9.25-9.25q8.14-1.11 9.25-9.25");
}

:global(.to8m3ibcr) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
