<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="yrf6kefpj"/><path class="a0sey-b7l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:search-answer-sharp" {...props}></Icon>
<style>
:global(.a0sey-b7l) {
  d: path("m17.25 3.75l.27 1.98L19.5 6l-1.98.27l-.27 1.98l-.27-1.98L15 6l1.98-.27zm-14.5 9.5h18.5m-18.5 4h18.5m-18.5 4h10");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yrf6kefpj) {
  d: path("M2.75 2.75h18.5v6.5H2.75zM6.25 6h7");
}

</style>
