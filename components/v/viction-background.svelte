<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="jgiwjcn0i"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:viction-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.jgiwjcn0i) {
  fill: var(--svg-color--f8f6d7, #f8f6d7);
  d: path("M20 4v6.923a32.3 32.3 0 0 1-8 .998a32.4 32.4 0 0 1-8-.998V4a32.4 32.4 0 0 0 8 .998c2.762 0 5.443-.346 8-.998M4 20v-6.923a32.3 32.3 0 0 1 8-.998c2.762 0 5.443.347 8 .998V20a32.4 32.4 0 0 0-8-.998c-2.762 0-5.443.346-8 .998");
}

:global(.mumfproca) {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
