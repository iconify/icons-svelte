<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ghsr-cb-v"/><path class="ataj3m0cv"/><path class="meg5w9b_w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:syllabus-sharp" {...props}></Icon>
<style>
:global(.ataj3m0cv) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.75 11.5h.01M7.75 16h.01");
}

:global(.ghsr-cb-v) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 2.75h16.5v18.5H3.75zM7.25 7h9.5");
}

:global(.meg5w9b_w) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 11.5h5.5m-5.5 4.5h4");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
