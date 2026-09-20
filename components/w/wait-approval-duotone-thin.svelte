<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nu-uxtbks"/><path class="uk4kcubrj"/><path class="gcy6xobcc"/><path class="b059umbje"/><path class="g922zfo1b"/><path class="p4jzd4blg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wait-approval-duotone-thin" {...props}></Icon>
<style>
:global(.b059umbje) {
  d: path("M9 9v3h2.5");
}

:global(.g922zfo1b) {
  d: path("M18 8v4");
}

:global(.gcy6xobcc) {
  d: path("M3 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nu-uxtbks) {
  fill: currentColor;
  d: path("M3 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.p4jzd4blg) {
  d: path("M17 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.uk4kcubrj) {
  fill: currentColor;
  d: path("M17 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
