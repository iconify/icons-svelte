<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="r0wydqb2x"/><path class="i6d8t0bvg"/><path class="x5t19bc6r"/><path class="v9bmzbkdm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:walking-stick-duotone-bold" {...props}></Icon>
<style>
:global(.i6d8t0bvg) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 21h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r0wydqb2x) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 21V8a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v9bmzbkdm) {
  d: path("M5 21h6");
}

:global(.x5t19bc6r) {
  d: path("M8 21V8a4 4 0 0 1 8 0");
}

</style>
