<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sb0axvnbu"/><path class="ymm7jyq0l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:smartphone-upload" {...props}></Icon>
<style>
:global(.sb0axvnbu) {
  d: path("M6 2.5h12v19H6ZM10.5 18h3M12 11.5V6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ymm7jyq0l) {
  d: path("M9.5 8.5L12 6l2.5 2.5m-5.5 6h6");
}

</style>
