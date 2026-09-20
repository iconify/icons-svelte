<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gjx_cybnq"/><path class="m7b08xyfb"/><path class="cfyvl-o0i"/><path class="mi_m6achy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:trigger-email-outline-thin" {...props}></Icon>
<style>
:global(.cfyvl-o0i) {
  d: path("M16 12h4");
}

:global(.gjx_cybnq) {
  d: path("M2 10a2 2 0 0 1 2 -2h7a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m7b08xyfb) {
  d: path("m4 9 3.5 3.5L11 9");
}

:global(.mi_m6achy) {
  d: path("m17 9 3 3 -3 3");
}

</style>
