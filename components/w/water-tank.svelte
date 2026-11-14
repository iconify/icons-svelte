<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b2g11-mpz"/><path class="gevrtubnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:water-tank" {...props}></Icon>
<style>
:global(.b2g11-mpz) {
  d: path("M4.5 4.5a7.5 2 0 1 0 15 0a7.5 2 0 1 0-15 0Z");
}

:global(.gevrtubnm) {
  d: path("M4.5 4.5v7a7.5 2 0 0 0 15 0v-7m-13 8.75L5 21.5m12.5-8.25L19 21.5m-16.5 0h19m-15.75-4h12.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
