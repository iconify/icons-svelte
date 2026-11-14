<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gavqc4b8l"/><path class="q8y5eov9f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:snooze" {...props}></Icon>
<style>
:global(.gavqc4b8l) {
  d: path("M4.5 13a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0ZM3 6l3-3m15 3l-3-3M6.5 18.5l-2 2m13-2l2 2");
}

:global(.q8y5eov9f) {
  d: path("M9.75 10.5h4.5l-4.5 5h4.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
