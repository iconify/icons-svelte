<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n-7xnfbas"/><path class="b2998ks9l"/><path class="zm2dyvb-o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:score-outline-regular" {...props}></Icon>
<style>
:global(.b2998ks9l) {
  d: path("m10 11 2 -2v7");
}

:global(.n-7xnfbas) {
  d: path("m12 3 7 7v4l-7 7 -7 -7v-4Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.zm2dyvb-o) {
  d: path("M9 16h6");
}

</style>
