<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="to0c2ub7t"><path class="xntj31bof"/><path class="upr2r56ap"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:terminal-duotone" {...props}></Icon>
<style>
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

:global(.xntj31bof) {
  d: path("M4 5L10.5571 10.6204C10.7899 10.8199 10.7899 11.1801 10.5571 11.3796L4 17");
}

</style>
