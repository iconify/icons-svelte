<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ppbx_abyw"/><path class="v-u0ijc7h"/><path class="b42rpjnun"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:user-edit-outline-regular" {...props}></Icon>
<style>
:global(.b42rpjnun) {
  d: path("M14.5 16.5V14l5 -5 2.5 2.5 -5 5Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ppbx_abyw) {
  d: path("M6 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.v-u0ijc7h) {
  d: path("M3 21a6 6 0 0 1 12 0");
}

</style>
