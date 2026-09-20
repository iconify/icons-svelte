<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e6eri9pjq"/><path class="ta4vmeb9o"/><path class="tbmc7jbly"/><path class="z0jk47bno"/><path class="b4x_isbqv"/><path class="d_6ujebpi"/><path class="jtt8g10_o"/><path class="ikiprn9sq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:turn-window-duotone-thin" {...props}></Icon>
<style>
:global(.b4x_isbqv) {
  d: path("M8 6H5v12h3");
}

:global(.d_6ujebpi) {
  d: path("M16 6h3v12h-3");
}

:global(.e6eri9pjq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 6H5v12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ikiprn9sq) {
  d: path("M9 14h6");
}

:global(.jtt8g10_o) {
  d: path("M9 10h6");
}

:global(.ta4vmeb9o) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 6h3v12h-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tbmc7jbly) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 10h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z0jk47bno) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 14h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
