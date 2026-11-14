<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gmf261bon"/><path class="irvweibbs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sommelier" {...props}></Icon>
<style>
:global(.gmf261bon) {
  d: path("M7 6.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m7.183 15H3c0-4.5 3.25-8 7.5-8c1.728 0 3.291.579 4.537 1.568");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.irvweibbs) {
  d: path("m9.118 16.559l.711.356a1.5 1.5 0 0 0 1.342 0l.711-.356A.773.773 0 0 1 13 17.25a.773.773 0 0 1-1.118.691l-.711-.356a1.5 1.5 0 0 0-1.342 0l-.711.356A.773.773 0 0 1 8 17.25a.773.773 0 0 1 1.118-.691M19 13.5v2c-1.5.5-2 1.5-2 2.5v3.5h4V18c0-1-.5-2-2-2.5");
}

</style>
