<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bpkgm8jdh"/><path class="dzv8xmg9v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:undo-2" {...props}></Icon>
<style>
:global(.bpkgm8jdh) {
  d: path("M4 9h11a5.5 5.5 0 0 1 0 11H8");
}

:global(.dzv8xmg9v) {
  d: path("M8 5L4 9l4 4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
