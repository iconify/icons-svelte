<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wvxot9bme"/><path class="d3mdw_zyn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:staff-task-list" {...props}></Icon>
<style>
:global(.d3mdw_zyn) {
  d: path("m6.75 11.25l1 1l2-2m2.25 1h5M6.75 15h3v3h-3ZM12 16.5h5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wvxot9bme) {
  d: path("M4 4.5h16v17H4Zm4-2v4m4-4v4m4-4v4");
}

</style>
