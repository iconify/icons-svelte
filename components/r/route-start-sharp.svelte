<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="zvb-krb3m"/><path class="qvoc8gbpg"/><path class="r82irb6gc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:route-start-sharp" {...props}></Icon>
<style>
:global(.qvoc8gbpg) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 17.5h.01");
}

:global(.r82irb6gc) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 17.5h5.5v-12h5.5");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.zvb-krb3m) {
  cx: 6.5px;
  cy: 17.5px;
  r: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
