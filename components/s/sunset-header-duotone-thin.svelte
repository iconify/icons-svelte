<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rtydvac2z"/><path class="lgv7os48g"/><path class="nojmwybsp"/><path class="yy7rcrbfy"/><path class="ffhg2obzl"/><path class="exx4qg62z"/><path class="o8od38cnm"/><path class="z5iv6lbtc"/><path class="xaedo1bnv"/><path class="omq19fbzw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sunset-header-duotone-thin" {...props}></Icon>
<style>
:global(.exx4qg62z) {
  d: path("M7 15a5 5 0 0 1 10 0");
}

:global(.ffhg2obzl) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m19 8 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lgv7os48g) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 18h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nojmwybsp) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 4.5V7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.o8od38cnm) {
  d: path("M4 18h16");
}

:global(.omq19fbzw) {
  d: path("m19 8 -2 2");
}

:global(.rtydvac2z) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 15a5 5 0 0 1 10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xaedo1bnv) {
  d: path("m5 8 2 2");
}

:global(.yy7rcrbfy) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m5 8 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z5iv6lbtc) {
  d: path("M12 4.5V7");
}

</style>
