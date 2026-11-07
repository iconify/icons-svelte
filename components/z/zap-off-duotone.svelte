<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="y57vpl4bn"/><path class="m1u1p6bxg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:zap-off-duotone" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.m1u1p6bxg) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m7 10l-2 2c-.369.369-.369 1 0 1h4a1 1 0 0 1 1 1v6c0 .369.631.369 1 0l3-3m3-3l2-2c.369-.369.369-1 0-1h-4a1 1 0 0 1-1-1V4c0-.369-.631-.369-1 0l-3 3M2 5l17 17");
}

:global(.y57vpl4bn) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m17 14l-7-7l3-3c.369-.369 1-.369 1 0v6a1 1 0 0 0 1 1h4c.369 0 .369.631 0 1Zm-6 6c-.369.369-1 .369-1 0v-6a1 1 0 0 0-1-1H5c-.369 0-.369-.631 0-1l2-2l7 7Z");
}

</style>
