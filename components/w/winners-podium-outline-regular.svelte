<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j8ri2qizx"/><path class="o243xubfu"/><path class="qqp18hbup"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:winners-podium-outline-regular" {...props}></Icon>
<style>
:global(.j8ri2qizx) {
  d: path("M8 21V6h8v15Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o243xubfu) {
  d: path("M2 21V11h6");
}

:global(.qqp18hbup) {
  d: path("M22 21v-7h-6");
}

</style>
