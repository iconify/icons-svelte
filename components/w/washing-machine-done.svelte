<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="trzc92byx"/><path class="pt9nk8v3k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:washing-machine-done" {...props}></Icon>
<style>
:global(.pt9nk8v3k) {
  d: path("M6.75 13.25a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm8 4.75l2 2L21 15.75");
}

:global(.trzc92byx) {
  d: path("M12.8 20H3V2.5h15v12.3M3 7h15");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
