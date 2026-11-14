<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l8k1b59ls"/><path class="lf0-u1c8y"/><path class="ka90l1-wp"/><path class="n1npu_o6y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:sunburn" {...props}></Icon>
<style>
:global(.ka90l1-wp) {
  fill: currentColor;
  d: path("M16.25 17.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

:global(.l8k1b59ls) {
  fill: currentColor;
  d: path("M11.472 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c.682 0 1.339.058 1.96.169");
}

:global(.lf0-u1c8y) {
  d: path("M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

:global(.n1npu_o6y) {
  d: path("M17.75 14.25h.01m2.49 1h.01m.99 2.5h.01m-1.01 2.5h.01m-2.51 1h.01m-2.51-1h.01m-1.01-2.5h.01m.99-2.5h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
