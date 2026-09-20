<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sknn5dbsy"/><path class="j7h3npb4b"/><path class="p-4c_po-t"/><path class="w89kumbyo"/><path class="mho7bk0jd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:vegan-duotone-regular" {...props}></Icon>
<style>
:global(.j7h3npb4b) {
  fill: currentColor;
  d: path("M12 13c0 -5 4 -8 9 -8 0 5 -4 8 -9 8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.mho7bk0jd) {
  d: path("M12 13c0 -5 4 -8 9 -8 0 5 -4 8 -9 8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p-4c_po-t) {
  d: path("M12 21v-8");
}

:global(.sknn5dbsy) {
  fill: currentColor;
  d: path("M12 13c0 -5 -4 -8 -9 -8 0 5 4 8 9 8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.w89kumbyo) {
  d: path("M12 13c0 -5 -4 -8 -9 -8 0 5 4 8 9 8");
}

</style>
