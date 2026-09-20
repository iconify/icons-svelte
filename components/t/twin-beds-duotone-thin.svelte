<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wa-vwbbwu"/><path class="iwb9d999q"/><path class="kte_8ab6e"/><path class="czqsgdbtp"/><path class="lpfop-b2k"/><path class="c3v3u_beb"/><path class="yt443xqvj"/><path class="i55cujbki"/><path class="hrbcgxb0f"/><path class="lue0cj-so"/><path class="shmft-b2f"/><path class="q45jzkbtp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:twin-beds-duotone-thin" {...props}></Icon>
<style>
:global(.c3v3u_beb) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 11V8.5h3.5V11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.czqsgdbtp) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 18v-7h8v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hrbcgxb0f) {
  d: path("M3 11V8.5h3.5V11");
}

:global(.i55cujbki) {
  d: path("M2 14h8");
}

:global(.iwb9d999q) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 14h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kte_8ab6e) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 11V8.5h3.5V11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lpfop-b2k) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 14h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lue0cj-so) {
  d: path("M14 18v-7h8v7");
}

:global(.q45jzkbtp) {
  d: path("M15 11V8.5h3.5V11");
}

:global(.shmft-b2f) {
  d: path("M14 14h8");
}

:global(.wa-vwbbwu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 18v-7h8v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yt443xqvj) {
  d: path("M2 18v-7h8v7");
}

</style>
