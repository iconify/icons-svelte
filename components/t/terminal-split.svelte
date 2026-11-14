<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h45fowb6u"/><path class="l6k7o3yui"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:terminal-split" {...props}></Icon>
<style>
:global(.h45fowb6u) {
  d: path("M3.5 3.5h17a1 1 0 0 1 1 1v15a1 1 0 0 1-1 1h-17a1 1 0 0 1-1-1v-15a1 1 0 0 1 1-1Zm8.5 0v17");
}

:global(.l6k7o3yui) {
  d: path("m5.25 9.5l2 2l-2 2m0 3.25h4m5.5-7.25l2 2l-2 2m0 3.25h4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
