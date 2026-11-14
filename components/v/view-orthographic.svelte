<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kpgchab7o"/><path class="ezz8p8b2a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:view-orthographic" {...props}></Icon>
<style>
:global(.ezz8p8b2a) {
  d: path("m3 7.5l9 4.5l9-4.5M12 12v9");
}

:global(.kpgchab7o) {
  d: path("m12 3l9 4.5v9L12 21l-9-4.5v-9Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
