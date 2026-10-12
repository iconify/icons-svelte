<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zr-svrb7u"/><path class="toofp-zpe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:smart-reply-sharp" {...props}></Icon>
<style>
:global(.toofp-zpe) {
  d: path("m9 5.75l-2.5 2.5l2.5 2.5m-2.5-2.5h7V11m4.25 3.25q.42 3.08 3.5 3.5q-3.08.42-3.5 3.5q-.42-3.08-3.5-3.5q3.08-.42 3.5-3.5Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zr-svrb7u) {
  d: path("M5.25 3.25h11v10.5H9.5l-3.6 3.1l-1.006.9l.006-1.35v-2.65l-2.172-.307l.022-2.193v-8z");
}

</style>
