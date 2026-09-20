<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s0c0pubvh"/><path class="bztdq0bdr"/><path class="mnwr0qhch"/><path class="h3z-uye4u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:straight-ahead-duotone-thin" {...props}></Icon>
<style>
:global(.bztdq0bdr) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 8 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h3z-uye4u) {
  d: path("m8 8 4 -4 4 4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mnwr0qhch) {
  d: path("M12 4v17");
}

:global(.s0c0pubvh) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 4v17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
