<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r8zggkb6v"/><path class="aphdxib6s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tree-palm-duocolor" {...props}></Icon>
<style>
:global(.aphdxib6s) {
  d: path("M12 8C9.875 4.211 4.241 4.837 3 9Zm9 1c-1.241-4.163-6.875-4.789-9-1Zm-9-1a7.52 7.52 0 0 0-7 8Zm7 8a7.52 7.52 0 0 0-7-8Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r8zggkb6v) {
  stroke-opacity: 0.4;
  d: path("M12 21V8");
}

</style>
