<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n8snr5b5g"/><path class="y2xvoyirj"/><path class="x5t19bc6r"/><path class="v9bmzbkdm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:walking-stick-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n8snr5b5g) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 21V8a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.v9bmzbkdm) {
  d: path("M5 21h6");
}

:global(.x5t19bc6r) {
  d: path("M8 21V8a4 4 0 0 1 8 0");
}

:global(.y2xvoyirj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 21h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
