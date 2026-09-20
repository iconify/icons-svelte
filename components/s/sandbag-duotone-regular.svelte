<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wxo-0_b_g"/><path class="sultgcbso"/><path class="v9mpn6bgd"/><path class="ear4nsbqw"/><path class="y8a66ib3e"/><path class="p4weyfsrl"/><path class="l9rn44bjs"/><path class="w0e70wbbt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sandbag-duotone-regular" {...props}></Icon>
<style>
:global(.ear4nsbqw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 21.5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

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

:global(.sultgcbso) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 13v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.v9mpn6bgd) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10.5 8 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w0e70wbbt) {
  d: path("M3 21.5h18");
}

:global(.wxo-0_b_g) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 4v15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y8a66ib3e) {
  d: path("M8 4v15");
}

</style>
