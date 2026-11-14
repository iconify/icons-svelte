<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l25jorets"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:scene-night" {...props}></Icon>
<style>
:global(.l25jorets) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.5 18a7.75 7.75 0 1 1-8-13a6 6 0 0 0 8 13m3.03-13.905l.348.554a1.5 1.5 0 0 0 .473.473l.554.348a.626.626 0 0 1 0 1.06l-.554.348a1.5 1.5 0 0 0-.473.473l-.348.554a.626.626 0 0 1-1.06 0l-.348-.554a1.5 1.5 0 0 0-.473-.473l-.554-.348a.626.626 0 0 1 0-1.06l.554-.348a1.5 1.5 0 0 0 .473-.473l.348-.554a.626.626 0 0 1 1.06 0");
}

</style>
