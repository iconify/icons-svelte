<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sn5-1xbuk"/><path class="gq5igqbpf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:veranda" {...props}></Icon>
<style>
:global(.gq5igqbpf) {
  d: path("M4 5.5v16m8-14v14m8-12v12M2.5 17h19");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.sn5-1xbuk) {
  fill: currentColor;
  d: path("m3.47 3.243l17.06 4.264a1.28 1.28 0 0 1 .97 1.243a.78.78 0 0 1-.97.757L3.47 5.243A1.28 1.28 0 0 1 2.5 4a.78.78 0 0 1 .97-.757");
}

</style>
