<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ve_xbsdkz"/><path class="e9dh58ngn"/><path class="m_7wrpotl"/><path class="ha1vlxxyu"/><path class="se99362hb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:stethoscope-outline-thin" {...props}></Icon>
<style>
:global(.e9dh58ngn) {
  d: path("M5 3a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.ha1vlxxyu) {
  d: path("M12 14v2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m_7wrpotl) {
  d: path("M17 3a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.se99362hb) {
  d: path("M9 19a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.ve_xbsdkz) {
  d: path("M6 4v4a6 6 0 0 0 12 0V4");
}

</style>
