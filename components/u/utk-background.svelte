<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="c7sbsnbbl"/><path class="qpoptryqj"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:utk-background" {...props}></Icon>
<style>
:global(.c7sbsnbbl) {
  fill: var(--svg-color--7c4dff, #7c4dff);
  d: path("M24 0H0v24h24z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.qpoptryqj) {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.86 12L20 8.152l-1.2-2.327l-6.537 2.667a.7.7 0 0 1-.524 0L5.2 5.827L4 8.152L11.14 12L4 15.848l1.2 2.327l6.538-2.667a.7.7 0 0 1 .523 0l6.537 2.668l1.2-2.328z");
}

</style>
