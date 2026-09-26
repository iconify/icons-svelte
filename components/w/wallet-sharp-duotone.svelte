<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jyo03ebxt"/><path class="ufgz6n_fm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:wallet-sharp-duotone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.jyo03ebxt) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 2L18 2C18.5523 2 19 2.4477 19 3L19 6L21 6C21.5523 6 22 6.4477 22 7L22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 5C2 3.3431 3.3431 2 5 2Z");
}

:global(.ufgz6n_fm) {
  d: path("M5 4C4.4477 4 4 4.4477 4 5C4 5.5523 4.4477 6 5 6L17 6L17 4L5 4ZM16 12L16 16L20 16L20 12L16 12Z");
}

</style>
