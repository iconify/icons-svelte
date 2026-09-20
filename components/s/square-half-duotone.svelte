<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="b17wkeb9u"/><path class="cj10fpzvh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:square-half-duotone" {...props}></Icon>
<style>
:global(.b17wkeb9u) {
  d: path("M208 56v144a8 8 0 0 1-8 8h-72V48h72a8 8 0 0 1 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cj10fpzvh) {
  d: path("M200 40H56a16 16 0 0 0-16 16v144a16 16 0 0 0 16 16h144a16 16 0 0 0 16-16V56a16 16 0 0 0-16-16M56 56h64v144H56Zm144 144h-64V56h64z");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

</style>
