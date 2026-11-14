<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="xxcfx35rt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:values-compass" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oy9aotbsd) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

:global(.xxcfx35rt) {
  d: path("m13.352 8.057l1.585 3.292a1.5 1.5 0 0 1 0 1.302l-1.585 3.292a1.5 1.5 0 0 1-2.704 0l-1.585-3.292a1.5 1.5 0 0 1 0-1.302l1.585-3.292a1.5 1.5 0 0 1 2.704 0M12 12h.01");
}

</style>
