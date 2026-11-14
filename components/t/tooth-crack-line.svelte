<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dz_qwxbde"/><path class="i50o_k5cx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:tooth-crack-line" {...props}></Icon>
<style>
:global(.dz_qwxbde) {
  d: path("M7 3C4.5 3 3.5 5 3.5 7.5c0 3 1.5 4.5 2 6.5l1.25 6c.25 1.25 1.75 1.25 2 0L10 15.5c.5-1.5 3.5-1.5 4 0l1.25 4.5c.25 1.25 1.75 1.25 2 0l1.25-6c.5-2 2-3.5 2-6.5C20.5 5 19.5 3 17 3c-2 0-3 1.25-5 1.25S9 3 7 3Z");
}

:global(.i50o_k5cx) {
  d: path("M12 4.25L10.5 7.5l2.5 2l-1.5 3.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
