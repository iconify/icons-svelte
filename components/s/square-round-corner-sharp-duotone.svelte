<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="msr9pk01t"/><path clip-rule="evenodd" class="m9g90kbtr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-round-corner-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.m9g90kbtr) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11 9.5C11.8284 9.5 12.5 10.1716 12.5 11C12.5 11.8284 11.8284 12.5 11 12.5C10.1716 12.5 9.5 11.8284 9.5 11C9.5 10.1716 10.1716 9.5 11 9.5Z");
  stroke: none;
}

:global(.msr9pk01t) {
  d: path("M3 22L3 11C3 6.5817 6.5817 3 11 3L22 3M11 11L5.3431 5.3431");
}

</style>
