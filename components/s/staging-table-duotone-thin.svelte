<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yj9_d6byd"/><path class="sx1m0u7ew"/><path class="nu4hkfkzg"/><path class="e4l4cb81r"/><path class="ffs26fbkv"/><path class="vnmw_qj9q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:staging-table-duotone-thin" {...props}></Icon>
<style>
:global(.e4l4cb81r) {
  d: path("M3 4v11h18V4");
}

:global(.ffs26fbkv) {
  d: path("M12 17v4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nu4hkfkzg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 8 4 4 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sx1m0u7ew) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 17v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vnmw_qj9q) {
  d: path("m8 8 4 4 4 -4");
}

:global(.yj9_d6byd) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 4v11h18V4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
