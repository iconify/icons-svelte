<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iouomczwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:spin-to-win" {...props}></Icon>
<style>
:global(.iouomczwm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0M12 2.5v19M3 8l18 8M3 16l18-8");
}

</style>
