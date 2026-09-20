<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGzFz7TdFx)" class="oerycacie"/><defs><linearGradient id="SVGzFz7TdFx" x1="11.999" x2="11.999" y1="3.275" y2="20.717" gradientUnits="userSpaceOnUse"><stop class="wnzh9-bom"/><stop offset="1" class="ius1tzbmn"/></linearGradient></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:trove" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.ius1tzbmn) {
  stop-color: var(--svg-color--746e89, #746e89);
}

:global(.oerycacie) {
  d: path("M14.897 19.198a2.83 2.83 0 0 0 2.515 1.52h2.172a1.413 1.413 0 0 0 1.254-2.066L13.254 4.04a1.417 1.417 0 0 0-2.51 0L3.16 18.652a1.412 1.412 0 0 0 1.255 2.065h1.93a2.84 2.84 0 0 0 2.464-1.434l2.144-3.793a2.13 2.13 0 0 1-.81-.816a2.25 2.25 0 1 1 3.713 0a2.14 2.14 0 0 1-.872.85z");
}

:global(.wnzh9-bom) {
  stop-color: var(--svg-color--6036ef, #6036ef);
}

</style>
