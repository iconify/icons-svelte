<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hls4jpboy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:switchbot" {...props}></Icon>
<style>
:global(.hls4jpboy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.284 42.239s21.614 4.755 24.482-4.201c3.492-10.903-19.298-17.185-15.769-28.075c2.762-8.518 22.72-4.53 22.72-4.53");
}

</style>
