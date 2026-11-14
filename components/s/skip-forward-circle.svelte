<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="bwyoklb5o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:skip-forward-circle" {...props}></Icon>
<style>
:global(.bwyoklb5o) {
  d: path("m10.86 10.152l.885.619a1.5 1.5 0 0 1 0 2.458l-.885.619a1.5 1.5 0 0 1-2.36-1.229v-1.238a1.5 1.5 0 0 1 2.36-1.229M15.5 8.5v7");
}

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

</style>
