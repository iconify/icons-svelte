<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sdux1ybki"/><path class="tgaio3eqw"/><path class="d2-8y_yyr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:sponsor-certificate" {...props}></Icon>
<style>
:global(.d2-8y_yyr) {
  d: path("M16 18.75v2.75l1.5-1l1.5 1v-2.75");
}

:global(.sdux1ybki) {
  d: path("M12.8 19.5H2.5v-16h19v9.2m-14-4.2h9m-10 4h6");
}

:global(.tgaio3eqw) {
  d: path("M14.75 16.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
