<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="tc3rjukod"/><path class="ac4p_wikp"/><path class="f2vh026ub"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sunglasses-outline-bold" {...props}></Icon>
<style>
:global(.ac4p_wikp) {
  d: path("M14 9h7v5a3.5 3.5 0 0 1 -7 0Z");
}

:global(.f2vh026ub) {
  d: path("M10 9h4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tc3rjukod) {
  d: path("M3 9h7v5a3.5 3.5 0 0 1 -7 0Z");
}

</style>
