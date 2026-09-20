<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o3j__tb-v"/><path class="uw099db1h"/><path class="ilcfk6b1a"/><path class="gop02zbrx"/><path class="r7xk8o29f"/><path class="qw7b_6b1t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:text-cursor-duotone-regular" {...props}></Icon>
<style>
:global(.gop02zbrx) {
  d: path("M8 4h8");
}

:global(.ilcfk6b1a) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 20h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o3j__tb-v) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 4h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qw7b_6b1t) {
  d: path("M8 20h8");
}

:global(.r7xk8o29f) {
  d: path("M12 4v16");
}

:global(.uw099db1h) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
