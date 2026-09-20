<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sjde2nyhb"/><path class="vd0jm7r_j"/><path class="r7xk8o29f"/><path class="gsl5knvuq"/><path class="p0o5ir5ue"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:text-columns-outline-regular" {...props}></Icon>
<style>
:global(.gsl5knvuq) {
  d: path("M15 8h6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p0o5ir5ue) {
  d: path("M15 16h6");
}

:global(.r7xk8o29f) {
  d: path("M12 4v16");
}

:global(.sjde2nyhb) {
  d: path("M3 8h6");
}

:global(.vd0jm7r_j) {
  d: path("M3 16h6");
}

</style>
