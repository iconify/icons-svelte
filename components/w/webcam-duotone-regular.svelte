<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x1xb02odd"/><path class="tbr--mb3k"/><path class="iqxmkybol"/><path class="xedmbxbzm"/><path class="tr6mw0eac"/><path class="jwnes9bsk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:webcam-duotone-regular" {...props}></Icon>
<style>
:global(.iqxmkybol) {
  d: path("M7 10a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

:global(.jwnes9bsk) {
  d: path("M8 19h8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tbr--mb3k) {
  fill: currentColor;
  d: path("M10 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.tr6mw0eac) {
  d: path("M12 15v4");
}

:global(.x1xb02odd) {
  fill: currentColor;
  d: path("M7 10a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xedmbxbzm) {
  d: path("M10 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
