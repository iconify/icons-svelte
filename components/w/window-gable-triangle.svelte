<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ummw4xshg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:window-gable-triangle" {...props}></Icon>
<style>
:global(.ummw4xshg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 15.5l8.5-12l8.5 12m-16.25 0h15.5a1.75 1.75 0 0 1 1.75 1.75v2A1.75 1.75 0 0 1 19.75 21H4.25a1.75 1.75 0 0 1-1.75-1.75v-2a1.75 1.75 0 0 1 1.75-1.75M12 3.5v12M6.75 11h10.5");
}

</style>
