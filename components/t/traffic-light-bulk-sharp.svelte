<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b6r8t1brw"/><path class="e1ajxz96l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:traffic-light-bulk-sharp" {...props}></Icon>
<style>
:global(.b6r8t1brw) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 2h10a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.e1ajxz96l) {
  d: path("M10.158 6.221a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m0 5a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m0 5a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558");
}

</style>
