<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wmtj7ubjb"/><path class="bw1nw8b2t"/><path class="wrji4lgnj"/><path class="f6186achz"/><path class="fg9400yys"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:temperature-range-outline-bold" {...props}></Icon>
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

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wmtj7ubjb) {
  d: path("M9.5 15V6a2.5 2.5 0 0 1 5 0v9a4.5 4.5 0 1 1 -5 0");
}

:global(.wrji4lgnj) {
  d: path("M12 8v7");
}

</style>
