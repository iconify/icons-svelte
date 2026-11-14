<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sszboac4b"/><path class="zy4sy1mti"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:speaker-tower" {...props}></Icon>
<style>
:global(.sszboac4b) {
  d: path("M7 2.5h10v19H7ZM12 6h.01M12 9.75h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zy4sy1mti) {
  d: path("M9 15.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

</style>
