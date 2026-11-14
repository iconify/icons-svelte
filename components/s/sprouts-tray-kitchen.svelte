<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lfek_0wtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sprouts-tray-kitchen" {...props}></Icon>
<style>
:global(.lfek_0wtd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14h19L20 20H4Zm3 0v-4m0 0c0-2 1.25-3 2.75-3c0 2-1.25 3-2.75 3m5.5 4V8m0 0c0-2 1.25-3 2.75-3c0 2-1.25 3-2.75 3m5.5 6v-4m0 0c0-2 1.25-3 2.75-3c0 2-1.25 3-2.75 3");
}

</style>
