<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ei_je2b_p"/><path class="tni6f7iwc"/><path class="ju8v6k8zc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:triangle-alert" {...props}></Icon>
<style>
:global(.ei_je2b_p) {
  d: path("M14.4051 4.39215C13.3181 2.53595 10.6819 2.53595 9.5949 4.39215L2.40063 16.6777C1.28536 18.5822 2.63072 21 4.80572 21H19.1943C21.3693 21 22.7146 18.5822 21.5994 16.6777L14.4051 4.39215Z");
}

:global(.ju8v6k8zc) {
  fill: currentColor;
  d: path("M13 17C13 17.5523 12.5523 18 12 18C11.4477 18 11 17.5523 11 17C11 16.4477 11.4477 16 12 16C12.5523 16 13 16.4477 13 17Z");
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tni6f7iwc) {
  d: path("M12 9V13");
}

</style>
