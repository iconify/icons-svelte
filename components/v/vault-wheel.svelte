<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rocslgbmd"/><path class="frulv0m7f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:vault-wheel" {...props}></Icon>
<style>
:global(.frulv0m7f) {
  d: path("M10 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2-2V2.75M13.75 11l6-3.5m-6 5.5l6 3.5M12 14v7.25M10.25 13l-6 3.5m6-5.5l-6-3.5");
}

:global(.rocslgbmd) {
  d: path("M6 12a6 6 0 1 0 12 0a6 6 0 1 0-12 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
