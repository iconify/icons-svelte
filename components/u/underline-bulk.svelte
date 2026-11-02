<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u7bjwhbit"/><path class="ibvqkvt5f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:underline-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.ibvqkvt5f) {
  d: path("M9 11a3 3 0 1 0 6 0V5a1 1 0 0 1 2 0v6a5 5 0 0 1-10 0V5a1 1 0 0 1 2 0Z");
}

:global(.u7bjwhbit) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 18h12a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2");
}

</style>
