<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="boj3k0b7v"/><path class="e0w4zj40u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:spring-sprout" {...props}></Icon>
<style>
:global(.boj3k0b7v) {
  d: path("M4 20.5c1.5-4 14.5-4 16 0Z");
}

:global(.e0w4zj40u) {
  d: path("M12 17.5v-7c0-4 2.5-6.5 7-6.5c0 4-2.5 6.5-7 6.5m0 3c-4 0-7-2-7-6c4 0 6.5 2 7 6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
