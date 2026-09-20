<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jc_qjhdwl"/><path class="foi-0jb9y"/><path class="tmjo8lbfp"/><path class="w-p5p7bpj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:usage-duotone-regular" {...props}></Icon>
<style>
:global(.foi-0jb9y) {
  d: path("M12 3h6a3 3 0 0 1 3 3v12a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V6a3 3 0 0 1 3 -3Z");
}

:global(.jc_qjhdwl) {
  fill: currentColor;
  d: path("M12 3h6a3 3 0 0 1 3 3v12a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V6a3 3 0 0 1 3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tmjo8lbfp) {
  d: path("M5.5 13h13");
}

:global(.w-p5p7bpj) {
  d: path("M5.5 16.5h13");
}

</style>
