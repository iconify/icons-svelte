<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rzmag9b2k"/><path class="dawc-hbdd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:treasury-collections" {...props}></Icon>
<style>
:global(.dawc-hbdd) {
  d: path("M13 5.75c0-.42-.43-.63-1-.75c-.7.12-1.12.47-1 1c-.12 1.05 2.12.6 2 2c.12.5-.35.88-1 1c-.6-.12-1.03-.38-1-.75m1-4V5m0 4v.75");
}

:global(.rzmag9b2k) {
  d: path("M2.5 14h5L9 16.5h6l1.5-2.5h5v5.5a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2Zm5.25-7a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
