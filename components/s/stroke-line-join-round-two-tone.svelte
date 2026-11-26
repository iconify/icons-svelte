<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pt2e2p5li"/><path class="smjgxhb7o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:stroke-line-join-round-two-tone" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pt2e2p5li) {
  stroke-opacity: 0.4;
  d: path("M11 21V12C11 11.4477 11.4477 11 12 11H21");
}

:global(.smjgxhb7o) {
  d: path("M3 21V11C3 6.5817 6.5817 3 11 3H21");
}

</style>
