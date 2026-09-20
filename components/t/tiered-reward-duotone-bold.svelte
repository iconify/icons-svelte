<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hmkpulkfg"/><path class="en5i8_b3r"/><path class="fvdm5rbex"/><path class="e_j-ypfpq"/><path class="adxensbci"/><path class="yzggow1fx"/><path class="e0q5_ylwf"/><path class="ux-gk6uae"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tiered-reward-duotone-bold" {...props}></Icon>
<style>
:global(.adxensbci) {
  d: path("M12 2a6.5 6.5 0 1 1 0 13 6.5 6.5 0 1 1 0 -13M9.5 14.5V22l2.5 -2.5 2.5 2.5v-7.5");
}

:global(.e_j-ypfpq) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 5v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e0q5_ylwf) {
  d: path("M12 6.5V11");
}

:global(.en5i8_b3r) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 8v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fvdm5rbex) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 6.5V11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hmkpulkfg) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 2a6.5 6.5 0 1 1 0 13 6.5 6.5 0 1 1 0 -13M9.5 14.5V22l2.5 -2.5 2.5 2.5v-7.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ux-gk6uae) {
  d: path("M15 5v6");
}

:global(.yzggow1fx) {
  d: path("M9 8v3");
}

</style>
