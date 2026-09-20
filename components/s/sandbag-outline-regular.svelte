<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y8a66ib3e"/><path class="p4weyfsrl"/><path class="l9rn44bjs"/><path class="w0e70wbbt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sandbag-outline-regular" {...props}></Icon>
<style>
:global(.l9rn44bjs) {
  d: path("m10.5 8 3 3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p4weyfsrl) {
  d: path("M16 13v6");
}

:global(.w0e70wbbt) {
  d: path("M3 21.5h18");
}

:global(.y8a66ib3e) {
  d: path("M8 4v15");
}

</style>
