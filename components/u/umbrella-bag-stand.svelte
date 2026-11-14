<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="axbe2qbpn"/><path class="k-skrej7y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:umbrella-bag-stand" {...props}></Icon>
<style>
:global(.axbe2qbpn) {
  d: path("M8 9h8v10.5H8ZM5.5 19.5h13v2h-13Z");
}

:global(.k-skrej7y) {
  d: path("M12 5.5L14.75 9L12 17.5L9.25 9Zm0 0v-1a1.75 1.75 0 0 0-3.5 0m3.5 1v12");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
