<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gby_5dbxz"/><path class="m6ifjboxi"/><path class="mte9rkbip"/><path class="e4l4cb81r"/><path class="ffs26fbkv"/><path class="vnmw_qj9q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:staging-table-duotone-regular" {...props}></Icon>
<style>
:global(.e4l4cb81r) {
  d: path("M3 4v11h18V4");
}

:global(.ffs26fbkv) {
  d: path("M12 17v4");
}

:global(.gby_5dbxz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 4v11h18V4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m6ifjboxi) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 17v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mte9rkbip) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m8 8 4 4 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vnmw_qj9q) {
  d: path("m8 8 4 4 4 -4");
}

</style>
