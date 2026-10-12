<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="b9mf971ok"/><path class="rfevj2b_f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:vhs-tape-sharp" {...props}></Icon>
<style>
:global(.b9mf971ok) {
  d: path("M2.75 5.5h18.5v13H2.75zm4 3h10.5");
}

:global(.rfevj2b_f) {
  d: path("M6.25 11.5h11.5v4H6.25zm3.5 2h.01m4.49 0h.01");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
