<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n3ijmobdd"/><path class="zgxuderfk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:table-cells-merge-duocolor-sharp" {...props}></Icon>
<style>
:global(.n3ijmobdd) {
  stroke-opacity: 0.4;
  d: path("M12 4v5m0 6v5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.zgxuderfk) {
  d: path("M4 4h16v16H4Zm0 5h16M4 15h16");
}

</style>
