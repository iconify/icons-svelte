<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nib7c1f4e"/><path class="dwhv-y_rw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:sandbox-box-sharp" {...props}></Icon>
<style>
:global(.dwhv-y_rw) {
  d: path("M9.25 5h5.5v9h-5.5zm0 3.5h-2m7.5 0h2m-7.5 3h-2m7.5 0h2M10.5 5l-.75-1.5M13.5 5l.75-1.5");
}

:global(.nib7c1f4e) {
  d: path("M2.75 9v12.25h18.5V9m-18.5 9.25c3-1.25 6-1.75 9.25-1.75s6.25.5 9.25 1.75");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
