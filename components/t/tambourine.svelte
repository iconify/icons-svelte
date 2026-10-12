<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><circle class="o5__hii-l"/><path class="r75vddc6t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tambourine" {...props}></Icon>
<style>
:global(.dbgvcxwad) {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o5__hii-l) {
  cx: 12px;
  cy: 12px;
  r: 4.5px;
}

:global(.r75vddc6t) {
  d: path("m18.5 14.48l-1.1 1.91m-4.3 2.49h-2.2m-4.3-2.49l-1.1-1.91m0-4.96l1.1-1.91m4.3-2.49h2.2m4.3 2.49l1.1 1.91");
}

</style>
