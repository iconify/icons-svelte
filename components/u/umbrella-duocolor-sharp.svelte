<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kol7kqbto"/><path class="wmm3s4_zx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:umbrella-duocolor-sharp" {...props}></Icon>
<style>
:global(.kol7kqbto) {
  stroke-opacity: 0.4;
  d: path("M12 12v7a2 2 0 1 0 4 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wmm3s4_zx) {
  d: path("M3 12a9 9 0 0 1 18 0z");
}

</style>
