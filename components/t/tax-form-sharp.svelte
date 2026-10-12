<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ny-05x5yz"/><path class="i824fubsr"/><path class="ec_urro1u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tax-form-sharp" {...props}></Icon>
<style>
:global(.ec_urro1u) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.75 14.5h.01m4.49 3.5h.01");
}

:global(.i824fubsr) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.25 2.75v5h5m-11 3h7.5m-.25 3.5l-5 4");
}

:global(.ny-05x5yz) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.25 2.75h-9.5v18.5h14.5V7.75Z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
