<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wyj9kwb_b"/><path class="n7d250moc"/><path class="jpf4_0b1i"/><path class="d9y6q7nzx"/><path class="k0h8jyb-f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:router-agent-duotone-thin" {...props}></Icon>
<style>
:global(.d9y6q7nzx) {
  d: path("m14 12 5 -5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jpf4_0b1i) {
  d: path("M9 12h5");
}

:global(.k0h8jyb-f) {
  d: path("m14 12 5 5");
}

:global(.n7d250moc) {
  d: path("M3 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.wyj9kwb_b) {
  fill: currentColor;
  d: path("M3 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
