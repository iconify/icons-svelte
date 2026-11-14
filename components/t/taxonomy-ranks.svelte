<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mwxxzhx5d"/><path class="wy-fvccem"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:taxonomy-ranks" {...props}></Icon>
<style>
:global(.mwxxzhx5d) {
  d: path("M9 5.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM2.5 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm13 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wy-fvccem) {
  d: path("M12 8.5v4M5.5 15v-2.5h13V15");
}

</style>
