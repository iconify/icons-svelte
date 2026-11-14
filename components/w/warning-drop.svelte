<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cd6ks4xal"/><path class="yqppunb1q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:warning-drop" {...props}></Icon>
<style>
:global(.cd6ks4xal) {
  d: path("m12 2.75l9.75 17.75H2.25ZM12 9v7.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yqppunb1q) {
  d: path("m9.5 13.75l2.5 2.5l2.5-2.5");
}

</style>
