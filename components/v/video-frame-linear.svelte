<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xvjk-cbox"/><path class="r_0pl6b2k"/><path class="txon6o65c"/><path class="uhck3lx6y"/><path class="d7k56tgtd"/><path class="yirxaabex"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:video-frame-linear" {...props}></Icon>
<style>
:global(.d7k56tgtd) {
  d: path("M17 17L21.5 17M2.5 17L7 17");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.r_0pl6b2k) {
  d: path("M17 2.5L17 21.5");
}

:global(.txon6o65c) {
  d: path("M7 2.5L7 21.5");
}

:global(.uhck3lx6y) {
  d: path("M2.5 7L7 7M17 7L21.5 7");
}

:global(.xvjk-cbox) {
  d: path("M12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C22 4.92893 22 7.28595 22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22Z");
}

:global(.yirxaabex) {
  d: path("M2 12H22");
}

</style>
