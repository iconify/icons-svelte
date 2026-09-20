<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tlj36_-3d"/><path class="lhk-ji-wo"/><path class="lh_8lcb-x"/><path class="icvc39peu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tidy-up-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.icvc39peu) {
  d: path("m9 7 3 3 3 -3");
}

:global(.lh_8lcb-x) {
  d: path("M12 4v6");
}

:global(.lhk-ji-wo) {
  d: path("M5 12v8h14v-8Z");
}

:global(.tlj36_-3d) {
  fill: currentColor;
  d: path("M5 12v8h14v-8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
