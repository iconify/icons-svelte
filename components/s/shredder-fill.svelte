<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="sc4dh4_ug"/><path class="whwffdyez"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:shredder-fill" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sc4dh4_ug) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 12L3 6C3 3.2386 5.2386 1 8 1L14 1C14.2652 1 14.5196 1.1054 14.7071 1.2929L20.7071 7.2929C20.8946 7.4804 21 7.7348 21 8L21 12C21 12.5523 20.5523 13 20 13L4 13C3.4477 13 3 12.5523 3 12ZM14 5C14 6.6568 15.3431 8 17 8L18.5858 8L14 3.4142L14 5Z");
  stroke: none;
}

:global(.whwffdyez) {
  d: path("M2 12L22 12M6 16L6 22M10 16L10 20M14 16L14 22M18 16L18 20");
}

</style>
