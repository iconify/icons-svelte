<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="mgjkkubsa"/><path class="vtw80ckxk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:star-seven" {...props}></Icon>
<style>
:global(.mgjkkubsa) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.43 3.9l1.42 2.97q.43.9 1.4.67l3.2-.74q.98-.22.54.68l-1.43 2.95q-.44.9.34 1.52l2.58 2.04q.78.62-.19.84l-3.21.72q-.98.22-.97 1.22l.01 3.29q0 1-.78.37l-2.56-2.05q-.78-.63-1.56 0l-2.56 2.05q-.78.63-.78-.37l.01-3.29q.01-1-.97-1.22l-3.21-.72q-.97-.22-.19-.84l2.58-2.04q.78-.62.34-1.52L5.01 7.48q-.44-.9.54-.68l3.2.74q.97.23 1.4-.67l1.42-2.97q.43-.9.86 0");
}

:global(.vtw80ckxk) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12.5h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
