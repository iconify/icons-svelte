<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sjev68umd"/><path class="oe-98mb0w"/><path class="vdq8lyksd"/><path class="vhnbtvbtn"/><path class="xyj-l9cjp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:winsorize-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oe-98mb0w) {
  d: path("M12 6v12");
}

:global(.sjev68umd) {
  d: path("M6 11v7");
}

:global(.vdq8lyksd) {
  d: path("M18 12v6");
}

:global(.vhnbtvbtn) {
  d: path("M3 8h18");
}

:global(.xyj-l9cjp) {
  d: path("M3 18h18");
}

</style>
