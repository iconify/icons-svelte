<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ghe12obwf"/><path class="ur6zukbah"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:water-bill" {...props}></Icon>
<style>
:global(.ghe12obwf) {
  d: path("M5 2.5h14v19L16.75 20l-2.25 1.5L12 20l-2.5 1.5L7.25 20L5 21.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ur6zukbah) {
  d: path("M12 5.5S8.5 9 8.5 11a3.5 3.5 0 0 0 7 0c0-2-3.5-5.5-3.5-5.5ZM8.5 17h7");
}

</style>
