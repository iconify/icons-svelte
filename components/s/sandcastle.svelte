<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uapk-rbxm"/><path class="n5w2i237e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sandcastle" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n5w2i237e) {
  d: path("M10 21v-5a2 2 0 0 1 4 0v5");
}

:global(.uapk-rbxm) {
  d: path("M4 21V11h4V8h2v3h4V8h2v3h4v10Z");
}

</style>
