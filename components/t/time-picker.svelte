<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kouzo9n3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:time-picker" {...props}></Icon>
<style>
:global(.kouzo9n3x) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0M12 5.5h.01M18.5 12h.01M12 18.5h.01M5.5 12h.01M12 12l3.25-3.25");
}

</style>
