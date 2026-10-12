<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oe3h_3w2y"/><circle class="b2vzpybzx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tennis-racket" {...props}></Icon>
<style>
:global(.b2vzpybzx) {
  cx: 18.5px;
  cy: 18.5px;
  r: 2px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oe3h_3w2y) {
  d: path("M17.59 3.88a6.25 5-35 1 1-7.18 10.24a6.25 5-35 1 1 7.18-10.24m0 0l-7.18 10.24M9.9 6.13l8.2 5.74m-7.69 2.25l-1.72 2.46m-.41-.29l.82.58q.82.57.25 1.39L7.91 20.3q-.57.82-1.39.25l-.82-.58q-.82-.57-.25-1.39l1.44-2.04q.57-.82 1.39-.25");
}

</style>
