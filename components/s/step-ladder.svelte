<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bh-okru0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:step-ladder" {...props}></Icon>
<style>
:global(.bh-okru0z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 21.5L10 3m4 0l6 18.5M9.5 3h5M8 9h5m-7 6h9");
}

</style>
