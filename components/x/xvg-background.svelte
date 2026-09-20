<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="gamng9bta"/><path class="w0e07hbxz"/><path class="dx07b9_zf"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:xvg-background" {...props}></Icon>
<style>
:global(.dx07b9_zf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 9.969L14.58 4H9.42z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.gamng9bta) {
  fill: var(--svg-color--34bde2, #34bde2);
  d: path("M24 0H0v24h24z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.w0e07hbxz) {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.645 4L12 15.355L7.355 4H5.29L12 20l6.71-16z");
}

</style>
