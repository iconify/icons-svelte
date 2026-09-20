<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="li5x4yeoz"/><path class="ed9actbwe"/><path class="xt7b-dbai"/><path class="kc8gmclyk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:spotlight-outline-thin" {...props}></Icon>
<style>
:global(.ed9actbwe) {
  d: path("M6 11.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kc8gmclyk) {
  d: path("M14 11.5h4");
}

:global(.li5x4yeoz) {
  d: path("M3 9a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.xt7b-dbai) {
  d: path("m9.5 13 2 2");
}

</style>
