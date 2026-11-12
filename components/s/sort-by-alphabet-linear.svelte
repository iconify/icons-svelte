<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dt3ds6bov"/><path class="z5nkh5rsk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sort-by-alphabet-linear" {...props}></Icon>
<style>
:global(.dt3ds6bov) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13 7H3m7 5H3m5 5H3");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.z5nkh5rsk) {
  fill: currentColor;
  d: path("M11.316 16.692a.75.75 0 1 0 1.368.616zM16.5 7l.684-.308a.75.75 0 0 0-1.368 0zm3.816 10.308a.75.75 0 1 0 1.368-.616zm-.952-3.944l.684-.308zm-5.728-.75a.75.75 0 0 0 0 1.5zm-.952 4.694l4.5-10l-1.368-.616l-4.5 10zm9-.616l-1.636-3.636l-1.368.615l1.636 3.637zm-1.636-3.636l-2.864-6.364l-1.368.616l2.864 6.363zm-.684-.442h-5.728v1.5h5.728z");
}

</style>
