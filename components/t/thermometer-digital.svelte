<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a-f6sfgvi"/><path class="sicqr7bvi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:thermometer-digital" {...props}></Icon>
<style>
:global(.a-f6sfgvi) {
  d: path("M12 2.5za3 3 0 0 1 3 3v8a3 3 0 0 1-3 3a3 3 0 0 1-3-3v-8a3 3 0 0 1 3-3m-1.25 14l.5 4c.15 1 1.35 1 1.5 0l.5-4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.sicqr7bvi) {
  d: path("M12 5.25za1.5 1.5 0 0 1 1.5 1.5v2a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5v-2a1.5 1.5 0 0 1 1.5-1.5m0 8.25h.01");
}

</style>
