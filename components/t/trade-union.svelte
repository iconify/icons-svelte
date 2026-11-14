<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fp8ryr5ub"/><path class="v--4khbeq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:trade-union" {...props}></Icon>
<style>
:global(.fp8ryr5ub) {
  d: path("M6.5 4.5h11V13h-11Zm2.75 0v3m2.75-3v3m2.75-3v3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v--4khbeq) {
  d: path("M6.5 9.5h3a1.5 1.5 0 0 1 0 3m-1 .5v6.5m7-6.5v6.5");
}

</style>
