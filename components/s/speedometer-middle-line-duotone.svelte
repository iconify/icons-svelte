<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gshkn9qqt"/><path class="ud0vn3b7v"/><path class="thq5dxb7d"/><path class="wvjt8gthe"/><path class="frg8avblm"/><path class="wurlbwzqw"/><path class="mm4sswb_u"/><path class="gqr5orb3s"/><path class="zu8q05b8q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:speedometer-middle-line-duotone" {...props}></Icon>
<style>
:global(.frg8avblm) {
  d: path("M5 5L6.5 6.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.gqr5orb3s) {
  d: path("M12 4.00021L12 2.00021");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.gshkn9qqt) {
  d: path("M22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2C17.5228 2 22 6.47715 22 12Z");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mm4sswb_u) {
  d: path("M19.9998 12L21.9998 12");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.thq5dxb7d) {
  d: path("M19 5L17.5 6.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.ud0vn3b7v) {
  d: path("M19 19L17.5 17.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.wurlbwzqw) {
  d: path("M2 12H4");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.wvjt8gthe) {
  d: path("M5 19L6.5 17.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.zu8q05b8q) {
  d: path("M15 12C15 13.6569 13.6569 15 12 15C10.3431 15 9 13.6569 9 12C9 11.3698 9.43408 10.4955 9.972 9.65412C10.7764 8.39585 11.1786 7.76672 12 7.76672C12.8214 7.76672 13.2236 8.39585 14.028 9.65412C14.5659 10.4955 15 11.3698 15 12Z");
}

</style>
