<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qjb--3b5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sleep-tracker" {...props}></Icon>
<style>
:global(.qjb--3b5m) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3v17.5H21m-13-3V13m4.5 4.5v-7m4.5 7V14m.5-11a3 3 0 1 0 3 4.5a3.5 3.5 0 0 1-3-4.5");
}

</style>
