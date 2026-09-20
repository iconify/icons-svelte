<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yt443xqvj"/><path class="i55cujbki"/><path class="hrbcgxb0f"/><path class="lue0cj-so"/><path class="shmft-b2f"/><path class="q45jzkbtp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:twin-beds-outline-regular" {...props}></Icon>
<style>
:global(.hrbcgxb0f) {
  d: path("M3 11V8.5h3.5V11");
}

:global(.i55cujbki) {
  d: path("M2 14h8");
}

:global(.lue0cj-so) {
  d: path("M14 18v-7h8v7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q45jzkbtp) {
  d: path("M15 11V8.5h3.5V11");
}

:global(.shmft-b2f) {
  d: path("M14 14h8");
}

:global(.yt443xqvj) {
  d: path("M2 18v-7h8v7");
}

</style>
