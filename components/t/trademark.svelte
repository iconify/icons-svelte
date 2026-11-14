<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l6n3pjb9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:trademark" {...props}></Icon>
<style>
:global(.l6n3pjb9c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7H10M6.25 7v10M13 17V7l3.75 5.5L20.5 7v10");
}

</style>
