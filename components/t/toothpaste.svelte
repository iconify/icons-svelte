<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dz6gliidf"/><path class="lsg4qfbit"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:toothpaste" {...props}></Icon>
<style>
:global(.dz6gliidf) {
  d: path("m2.5 4.5l10 1l2.5 2v3l-2.5 2l-10 1ZM15 7h3.5v4H15ZM5 4.75v8.5");
}

:global(.lsg4qfbit) {
  d: path("M18.5 9c3 0 3.25 4.5 0 5.5c-3 1-4 4.5-1 5h3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
