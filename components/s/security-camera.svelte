<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chgkdvbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:security-camera" {...props}></Icon>
<style>
:global(.chgkdvbwi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.025 3.713l6.762 1.812a3.5 3.5 0 0 1 2.474 4.287a3.5 3.5 0 0 1-4.286 2.475l-6.762-1.812a3.5 3.5 0 0 1-2.474-4.287a3.5 3.5 0 0 1 4.286-2.475M12 13v4h8m.5-3.5v7M6 8h.01");
}

</style>
