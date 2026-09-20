<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cg0a9co7b"/><path class="ha190wb6v"/><path class="d27-dpb3f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sunscreen-outline-regular" {...props}></Icon>
<style>
:global(.cg0a9co7b) {
  d: path("M7 21V8h10v13Z");
}

:global(.d27-dpb3f) {
  d: path("M9 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.ha190wb6v) {
  d: path("M10 8V4h4v4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
