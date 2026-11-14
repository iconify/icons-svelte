<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qkkt5rzvn"/><path class="ob30dxblc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:topiary-ball" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ob30dxblc) {
  d: path("M9.25 7.25a3 3 0 0 1 2.25-2");
}

:global(.qkkt5rzvn) {
  d: path("M6.25 8.25a5.75 5.75 0 1 0 11.5 0a5.75 5.75 0 1 0-11.5 0M12 14v2.5m-5.5 0h11l-1.25 5h-8.5Z");
}

</style>
