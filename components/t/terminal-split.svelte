<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="joqwcx3og"/><path class="l6k7o3yui"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:terminal-split" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.joqwcx3og) {
  d: path("M7.75 3.5h8.5a5.25 5.25 0 0 1 5.25 5.25v6.5a5.25 5.25 0 0 1-5.25 5.25h-8.5a5.25 5.25 0 0 1-5.25-5.25v-6.5A5.25 5.25 0 0 1 7.75 3.5m4.25 0v17");
}

:global(.l6k7o3yui) {
  d: path("m5.25 9.5l2 2l-2 2m0 3.25h4m5.5-7.25l2 2l-2 2m0 3.25h4");
}

</style>
