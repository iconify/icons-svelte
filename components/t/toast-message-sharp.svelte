<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pw7p-85ys"/><path class="oqjj3z8ac"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:toast-message-sharp" {...props}></Icon>
<style>
:global(.oqjj3z8ac) {
  d: path("M7 12.25h10v5H7zm2.5 2.5h5");
}

:global(.pw7p-85ys) {
  d: path("M2.75 3.75h18.5v16.5H2.75z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
