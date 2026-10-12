<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zwbos_99n"/><path class="jxno-rbej"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tandoor" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jxno-rbej) {
  d: path("M10.5 21.25V20a1.5 1.5 0 0 1 3 0v1.25m-7-6.75c3.5 1 7.5 1 11 0");
}

:global(.zwbos_99n) {
  d: path("M8.75 9h6.5c2.5 2 4.5 5 4.5 8.75v1.75A1.75 1.75 0 0 1 18 21.25H6a1.75 1.75 0 0 1-1.75-1.75v-1.75c0-3.75 2-6.75 4.5-8.75M12 2.75Q13.5 4.025 13.5 5a1.5 1.5 0 0 1-3 0q0-.975 1.5-2.25");
}

</style>
