<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yxoiahs6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:thunderstorm" {...props}></Icon>
<style>
:global(.yxoiahs6i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 14.5a4.25 4.25 0 0 1 .5-8a5 5 0 0 1 9 .75a3.75 3.75 0 0 1 1 7.25Zm6 0L10.5 18h3L11 21.5m-4-4.25l-1 3m11.5-3l-1 3");
}

</style>
