<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f0ldmmbbm"/><path class="nuutkyboq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:temperature-celsius-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.f0ldmmbbm) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2.236 5.832A3 3 0 1 1 7.763 8.17a3 3 0 0 1-5.527-2.338m2.057 1.875a.999.999 0 1 0 1.414-1.414a.999.999 0 1 0-1.414 1.414");
}

:global(.nuutkyboq) {
  d: path("M18 6h-2a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h2a2 2 0 0 0 2-2a1 1 0 0 1 2 0a3.98 3.98 0 0 1-1.172 2.828A3.98 3.98 0 0 1 18 20h-2a4 4 0 0 1-4-4V8a4 4 0 0 1 4-4h2c1.064 0 2.078.418 2.828 1.172A3.98 3.98 0 0 1 22 8a1 1 0 0 1-2 0a2 2 0 0 0-2-2");
}

</style>
