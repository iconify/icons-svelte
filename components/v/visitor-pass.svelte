<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="on5961gga"/><path class="j7vio8fah"/><path class="br1by-bfe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:visitor-pass" {...props}></Icon>
<style>
:global(.br1by-bfe) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 18.25h5.5");
}

:global(.j7vio8fah) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 14.25h.01");
}

:global(.on5961gga) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 10.25v-4.5a2 2 0 0 1 2-2h10.5a2 2 0 0 1 2 2v4.5ZM10.5 7h3m-8.75 3.25h14.5v9a2 2 0 0 1-2 2H6.75a2 2 0 0 1-2-2Z");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
