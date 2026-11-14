<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qr9eccc4h"/><path class="xuin6t60b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:tote-bag" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qr9eccc4h) {
  d: path("M6.327 8h11.346a2.625 2.625 0 0 1 2.618 2.819l-.611 8.25a2.625 2.625 0 0 1-2.618 2.431H6.938a2.625 2.625 0 0 1-2.618-2.431l-.611-8.25A2.625 2.625 0 0 1 6.327 8");
}

:global(.xuin6t60b) {
  d: path("M8.5 11V6a3.5 3.5 0 0 1 7 0v5");
}

</style>
