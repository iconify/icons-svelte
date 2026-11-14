<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x5acz0biv"/><path class="z6p9osteo"/><path class="udg3cbi9q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:size-sticker-strip" {...props}></Icon>
<style>
:global(.udg3cbi9q) {
  d: path("M9 7.5V15h3.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x5acz0biv) {
  d: path("M6 7.5H3.5a1 1 0 0 0-1 1v7a1 1 0 0 0 1 1H6m12-9h2.5a1 1 0 0 1 1 1v7a1 1 0 0 1-1 1H18M7.5 4h9A1.5 1.5 0 0 1 18 5.5v10L13.5 20h-6A1.5 1.5 0 0 1 6 18.5v-13A1.5 1.5 0 0 1 7.5 4Z");
}

:global(.z6p9osteo) {
  fill: currentColor;
  d: path("m18 15.5l-3.75.5l-.75 4Z");
}

</style>
