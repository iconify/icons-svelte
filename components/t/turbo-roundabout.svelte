<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="go6cuvb6t"/><path class="j1jcv9bug"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:turbo-roundabout" {...props}></Icon>
<style>
:global(.go6cuvb6t) {
  d: path("M9.5 12a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM12 6.5a6 6 0 0 1 6 6q0 4 3 7m-9-2a6 6 0 0 1-6-6q0-4-3-7");
}

:global(.j1jcv9bug) {
  d: path("M21 16.5v3h-3M3 7.5v-3h3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
