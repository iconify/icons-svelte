<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uf9cmdbsc"/><path class="ji82kcb9n"/><path class="weeoombgx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:scrollbar-horizontal" {...props}></Icon>
<style>
:global(.ji82kcb9n) {
  d: path("M7 9.75L4.75 12L7 14.25m10-4.5L19.25 12L17 14.25");
}

:global(.uf9cmdbsc) {
  d: path("M2 7h20v10H2Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.weeoombgx) {
  fill: currentColor;
  d: path("M9.75 10.75h4.5v2.5h-4.5Z");
}

</style>
