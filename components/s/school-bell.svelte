<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kmi_5qe8s"/><path class="uza32lbvm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:school-bell" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kmi_5qe8s) {
  d: path("M5.5 17.5C6.75 16 7 14 7 12a5 5 0 0 1 10 0c0 2 .25 4 1.5 5.5Z");
}

:global(.uza32lbvm) {
  d: path("M12 2.5zA1.5 1.5 0 0 1 13.5 4v1.5A1.5 1.5 0 0 1 12 7a1.5 1.5 0 0 1-1.5-1.5V4A1.5 1.5 0 0 1 12 2.5m0 18h.01");
}

</style>
