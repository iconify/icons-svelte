<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="dfn31__uv"/><path class="deo8mbctu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:steel-beam" {...props}></Icon>
<style>
:global(.deo8mbctu) {
  d: path("M4.75 15.75h14.5M12 3v4.5m0 0l-6.5 5.75M12 7.5l6.5 5.75");
}

:global(.dfn31__uv) {
  width: 18.5px;
  height: 5px;
  x: 2.75px;
  y: 13.25px;
  rx: 1px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
