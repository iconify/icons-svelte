<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dgmhgnb8l"/><path class="rflqhgbfy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:snorkel-sharp" {...props}></Icon>
<style>
:global(.dgmhgnb8l) {
  d: path("M2.75 10.5v-2h15v8h-4.5l-2.25-2l-2.25 2h-6v-3Z");
}

:global(.rflqhgbfy) {
  d: path("M20.5 2.75v18h-7v-2");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
