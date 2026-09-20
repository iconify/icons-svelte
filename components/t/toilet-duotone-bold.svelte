<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="l8n_uacwg"/><path class="vu337ub9w"/><path class="y1fttzc7x"/><path class="cn55ckwew"/><path class="jnf_2db5t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:toilet-duotone-bold" {...props}></Icon>
<style>
:global(.cn55ckwew) {
  d: path("M5 10h14v3a7.4 7.4 0 0 1 -14 0Z");
}

:global(.jnf_2db5t) {
  d: path("M12 18v3");
}

:global(.l8n_uacwg) {
  fill: currentColor;
  d: path("M5 2v5h8V2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vu337ub9w) {
  fill: currentColor;
  d: path("M5 10h14v3a7.4 7.4 0 0 1 -14 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.y1fttzc7x) {
  d: path("M5 2v5h8V2Z");
}

</style>
