<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="murw5tb-p"/><path class="emd5ykbgi"/><path class="e2w7612gy"/><path class="b4mmc1byx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:text-cursor-input-outline-thin" {...props}></Icon>
<style>
:global(.b4mmc1byx) {
  d: path("M6.5 14h3");
}

:global(.e2w7612gy) {
  d: path("M6.5 10h3");
}

:global(.emd5ykbgi) {
  d: path("M8 10v4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.murw5tb-p) {
  d: path("M2 9a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
