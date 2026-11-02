<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="thj7n1o7v"/><path class="k8y94cc3e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tornado-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.k8y94cc3e) {
  d: path("M21 3a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm-3 4a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Zm1 4a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Z");
}

:global(.thj7n1o7v) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 15a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2Zm-5 6H9a1 1 0 0 1 0-2h2a1 1 0 0 1 0 2");
}

</style>
