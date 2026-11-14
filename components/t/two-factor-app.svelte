<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="otft43bjg"/><path class="f_tq34bqb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:two-factor-app" {...props}></Icon>
<style>
:global(.f_tq34bqb) {
  d: path("M8.75 11.5h6.5V17h-6.5Zm1.5 0v-2a1.75 1.75 0 0 1 3.5 0v2");
}

:global(.otft43bjg) {
  d: path("M6 2h12v20H6Zm4.5 2.75h3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
