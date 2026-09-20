<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rwa7yr8zy"/><path class="j8lijfbga"/><path class="wmtj7ubjb"/><path class="bw1nw8b2t"/><path class="wrji4lgnj"/><path class="f6186achz"/><path class="fg9400yys"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:temperature-range-duotone-regular" {...props}></Icon>
<style>
:global(.bw1nw8b2t) {
  d: path("M10 17.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.f6186achz) {
  d: path("M15 8h4");
}

:global(.fg9400yys) {
  d: path("M15 13h4");
}

:global(.j8lijfbga) {
  fill: currentColor;
  d: path("M10 17.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rwa7yr8zy) {
  fill: currentColor;
  d: path("M9.5 15V6a2.5 2.5 0 0 1 5 0v9a4.5 4.5 0 1 1 -5 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.wmtj7ubjb) {
  d: path("M9.5 15V6a2.5 2.5 0 0 1 5 0v9a4.5 4.5 0 1 1 -5 0");
}

:global(.wrji4lgnj) {
  d: path("M12 8v7");
}

</style>
