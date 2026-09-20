<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="y86m7phcf"/><path class="d_x824bsi"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:strk-background" {...props}></Icon>
<style>
:global(.d_x824bsi) {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 10.316V4l-5.053 9.684H12V20l5.052-9.684z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.y86m7phcf) {
  fill: var(--svg-color--277fe3, #277fe3);
  d: path("M24 0H0v24h24z");
}

</style>
