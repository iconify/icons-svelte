<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ysnrr8bfy"/><path class="e2pqbvira"/><circle class="rzyzgqcqn"/><path class="ou3-6xb0d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:shalimar-garden" {...props}></Icon>
<style>
:global(.e2pqbvira) {
  d: path("M12 5v4m0 6v4m-7-7h4m6 0h4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ou3-6xb0d) {
  d: path("M7.5 5.75c.8.9 1.2 1.9 1.2 2.8a1.2 1.2 0 0 1-2.4 0c0-.9.4-1.9 1.2-2.8m9 0c.8.9 1.2 1.9 1.2 2.8a1.2 1.2 0 0 1-2.4 0c0-.9.4-1.9 1.2-2.8m-9 8.5c.8.9 1.2 1.9 1.2 2.8a1.2 1.2 0 0 1-2.4 0c0-.9.4-1.9 1.2-2.8m9 0c.8.9 1.2 1.9 1.2 2.8a1.2 1.2 0 0 1-2.4 0c0-.9.4-1.9 1.2-2.8");
}

:global(.rzyzgqcqn) {
  cx: 12px;
  cy: 12px;
  r: 2.25px;
}

:global(.ysnrr8bfy) {
  width: 17.5px;
  height: 17.5px;
  x: 3.25px;
  y: 3.25px;
  rx: 2px;
}

</style>
