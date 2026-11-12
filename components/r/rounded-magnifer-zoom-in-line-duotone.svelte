<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGDK52mvFV"><g class="k2u665ban"><circle class="pt9xvrdoi"/><path class="qw-wiacjh"/></g></mask></defs><path mask="url(#SVGDK52mvFV)" class="w49j0rbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rounded-magnifer-zoom-in-line-duotone" {...props}></Icon>
<style>
:global(.k2u665ban) {
  fill: none;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pt9xvrdoi) {
  cx: 11px;
  cy: 11px;
  r: 9px;
  stroke: var(--svg-color--gray, gray);
}

:global(.qw-wiacjh) {
  stroke: var(--svg-color--fff, #fff);
  stroke-linecap: round;
  d: path("M9 11h2m0 0h2m-2 0v2m0-2V9m10.812 11.975c-.063.095-.176.208-.403.434c-.226.227-.34.34-.434.403a1.13 1.13 0 0 1-1.62-.408c-.053-.1-.099-.254-.19-.561c-.101-.335-.151-.503-.161-.621a1.13 1.13 0 0 1 1.218-1.218c.118.01.285.06.621.16c.307.092.46.138.56.192a1.13 1.13 0 0 1 .409 1.619Z");
}

:global(.w49j0rbvv) {
  fill: currentColor;
  d: path("M0 0h24v24H0z");
}

</style>
