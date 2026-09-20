<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kf9a53s1u"/><path class="twefftbsb"/><path class="r3s5lrfhb"/><path class="zv_796-4v"/><path class="y8a66ib3e"/><path class="p4weyfsrl"/><path class="l9rn44bjs"/><path class="w0e70wbbt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sandbag-duotone-bold" {...props}></Icon>
<style>
:global(.kf9a53s1u) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 4v15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l9rn44bjs) {
  d: path("m10.5 8 3 3");
}

:global(.p4weyfsrl) {
  d: path("M16 13v6");
}

:global(.r3s5lrfhb) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m10.5 8 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.twefftbsb) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 13v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w0e70wbbt) {
  d: path("M3 21.5h18");
}

:global(.y8a66ib3e) {
  d: path("M8 4v15");
}

:global(.zv_796-4v) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 21.5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
