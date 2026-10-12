<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="asdf1bcrw"/><path class="dkw9b6vju"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:snowman-sharp" {...props}></Icon>
<style>
:global(.asdf1bcrw) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.52 9.94a3.75 3.75 0 1 1 2.96 0a5.75 5.75 0 1 1-2.96 0Zm2.23-3.44l4.5 1");
}

:global(.dkw9b6vju) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 14.5h.01M12 18h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
