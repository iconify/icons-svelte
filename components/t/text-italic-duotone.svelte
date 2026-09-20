<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="mlv7bibdo"/><path class="ao82dzbke"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:text-italic-duotone" {...props}></Icon>
<style>
:global(.ao82dzbke) {
  d: path("M200 56a8 8 0 0 1-8 8h-34.23L115.1 192H144a8 8 0 0 1 0 16H64a8 8 0 0 1 0-16h34.23L140.9 64H112a8 8 0 0 1 0-16h80a8 8 0 0 1 8 8");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.mlv7bibdo) {
  d: path("m192 56l-48 144H64l48-144Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
