<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o30ot4b6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:vector-arrow" {...props}></Icon>
<style>
:global(.o30ot4b6c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.5 19.5l15-15m-7 0h7v7");
}

</style>
