<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mzvcb5byi"/><path class="z3zttqj_r"/><path class="a_gwgkc5a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:speculative-decode-outline-regular" {...props}></Icon>
<style>
:global(.a_gwgkc5a) {
  d: path("m16 17 2 2 4 -4");
}

:global(.mzvcb5byi) {
  d: path("m3 6 6 6 -6 6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.z3zttqj_r) {
  d: path("m10 6 6 6 -6 6");
}

</style>
