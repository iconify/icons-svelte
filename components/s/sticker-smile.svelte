<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vvhybz9th"/><path class="b84be77hi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:sticker-smile" {...props}></Icon>
<style>
:global(.b84be77hi) {
  d: path("M21.5 12L15 15l-3 6.5m-4.25-13h.01m4.49 0h.01m.771 4.25a3.5 3.5 0 0 1-6.062 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vvhybz9th) {
  d: path("M12 21.5a9.5 9.5 0 1 1 9.5-9.5z");
}

</style>
