<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lyyswacbl"/><path class="uxsptjbvt"/><path class="druahpb2o"/><path class="d0m2g8bjt"/><path class="slu778b9b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sni-outline-thin" {...props}></Icon>
<style>
:global(.d0m2g8bjt) {
  d: path("m7 21 3 -3h7");
}

:global(.druahpb2o) {
  d: path("M6 11h9");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lyyswacbl) {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.slu778b9b) {
  d: path("M18.5 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.uxsptjbvt) {
  d: path("M6 7h12");
}

</style>
