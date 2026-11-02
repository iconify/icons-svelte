<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ouhcolk2v"/><path class="nvlp5xb3c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shopping-cart-duocolor-round" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nvlp5xb3c) {
  d: path("M3 4c.846 0 1.662.816 2 2l2 7c.507 1.776 2.14 3 4 3h6c.796 0 1.602-.806 2-2l1-3c.492-1.476-.524-3-2-3H6");
}

:global(.ouhcolk2v) {
  stroke-opacity: 0.4;
  d: path("M8 20a1 1 0 1 0 2 0a1 1 0 0 0-2 0m9 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
