<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mjb9t-b_f"/><path class="uw5kuce7r"/><path class="h66tg3bvx"/><path class="oe-98mb0w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:windsock-duotone-thin" {...props}></Icon>
<style>
:global(.h66tg3bvx) {
  d: path("M6 6h6l6 6 -6 6H6Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mjb9t-b_f) {
  fill: currentColor;
  d: path("M6 6h6l6 6 -6 6H6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.oe-98mb0w) {
  d: path("M12 6v12");
}

:global(.uw5kuce7r) {
  d: path("M3 3v18");
}

</style>
