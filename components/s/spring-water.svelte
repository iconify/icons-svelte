<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j05entbca"/><path class="id_t5lzlv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:spring-water" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.id_t5lzlv) {
  d: path("M12 15.5v-9C11 3.5 7 3 5.5 9M12 6.5c1-3 5-3.5 6.5 2.5m-13 3h.01m12.99 0h.01");
}

:global(.j05entbca) {
  d: path("M2.5 18.5a9.5 3 0 1 0 19 0a9.5 3 0 1 0-19 0");
}

</style>
