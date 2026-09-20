<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v8t37dedd"/><path class="gg6jr8oaf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:step-limit-outline-regular" {...props}></Icon>
<style>
:global(.gg6jr8oaf) {
  d: path("M21 4v16");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.v8t37dedd) {
  d: path("M3 6h5v5h5v5h5");
}

</style>
