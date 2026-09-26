<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="to0c2ub7t"><path class="p6xm5x-rc"/><path class="upr2r56ap"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:terminal-asterisk-two-tone" {...props}></Icon>
<style>
:global(.p6xm5x-rc) {
  d: path("M8 5L8 15M4 13L12 7M4 7L12 13");
}

:global(.to0c2ub7t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.upr2r56ap) {
  stroke-opacity: 0.4;
  d: path("M20 19L13 19");
}

</style>
