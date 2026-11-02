<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qehqx7n1d"/><path class="g4coswb2x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shopping-cart-alt-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.g4coswb2x) {
  d: path("M3 3h2a1 1 0 0 1 .949.684L6.721 6H21a1.002 1.002 0 0 1 .949 1.316l-2 6A1 1 0 0 1 19 14H9.387l.334 1H18a3 3 0 1 1-2.829 2h-2.342a3 3 0 1 1-4.93-1.141L4.279 5H3a1 1 0 0 1 0-2m5.721 9h9.558l1.334-4H7.387Zm.572 5.293a.999.999 0 1 0 1.414 1.414a.999.999 0 1 0-1.414-1.414m8 0a.999.999 0 1 0 1.414 1.414a.999.999 0 1 0-1.414-1.414");
}

:global(.qehqx7n1d) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 7h15l-2 6H8Z");
}

</style>
