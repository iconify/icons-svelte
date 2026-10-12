<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="y1uw5ib8l"/><circle class="jgyxsrxaa"/><circle class="qcx76zaxv"/><circle class="ufo-xpbwx"/><path class="ut97a0cqw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:timeline-posts-sharp" {...props}></Icon>
<style>
:global(.jgyxsrxaa) {
  cx: 6px;
  cy: 5px;
  r: 1.75px;
}

:global(.qcx76zaxv) {
  cx: 6px;
  cy: 12px;
  r: 1.75px;
}

:global(.ufo-xpbwx) {
  cx: 6px;
  cy: 19px;
  r: 1.75px;
}

:global(.ut97a0cqw) {
  d: path("M10.75 2.75h10.5v4.5h-10.5zm0 7h10.5v4.5h-10.5zm0 7h10.5v4.5h-10.5z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y1uw5ib8l) {
  d: path("M6 6.75v3.5m0 3.5v3.5");
}

</style>
