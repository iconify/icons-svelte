<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ds000fbnl"/><path class="bj2hlhbfp"/><path class="ukjt4fb6s"/><path class="ids981bkm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:self-consistency-outline-regular" {...props}></Icon>
<style>
:global(.bj2hlhbfp) {
  d: path("M3 12h12");
}

:global(.ds000fbnl) {
  d: path("M3 7h12");
}

:global(.ids981bkm) {
  d: path("m17 11 2 2 3 -3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ukjt4fb6s) {
  d: path("M3 17h12");
}

</style>
