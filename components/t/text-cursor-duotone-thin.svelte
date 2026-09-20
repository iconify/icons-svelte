<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hbae24-ac"/><path class="wj8ybccjk"/><path class="drz60ab5x"/><path class="gop02zbrx"/><path class="r7xk8o29f"/><path class="qw7b_6b1t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:text-cursor-duotone-thin" {...props}></Icon>
<style>
:global(.drz60ab5x) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 20h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gop02zbrx) {
  d: path("M8 4h8");
}

:global(.hbae24-ac) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 4h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qw7b_6b1t) {
  d: path("M8 20h8");
}

:global(.r7xk8o29f) {
  d: path("M12 4v16");
}

:global(.wj8ybccjk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
