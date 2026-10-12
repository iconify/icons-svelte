<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rtf8i4bvm"/><circle class="qme-dacyk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:salad-sharp" {...props}></Icon>
<style>
:global(.qme-dacyk) {
  cx: 7.25px;
  cy: 8px;
  r: 2px;
}

:global(.rtf8i4bvm) {
  d: path("M4 12.5h16l.804-.002l-.054.802A8 8 0 0 1 16 19.45V21H8v-1.55a8 8 0 0 1-4.75-6.15l-.054-.802zm8.5-2.5C11 7 12 4 15.75 2.75c1.75 3 .25 6-3.25 7.25Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
