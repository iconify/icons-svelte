<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="e3c-cvbig"/><path class="yn6zku7qr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shopping-basket-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.e3c-cvbig) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3.038 10.275A1 1 0 0 1 4 9h16a1 1 0 0 1 .962 1.275l-2 7c-.396 1.384-1.262 2.775-2.602 3.41A3.2 3.2 0 0 1 15 21H9a3.2 3.2 0 0 1-1.36-.315c-1.34-.635-2.206-2.026-2.602-3.41Z");
}

:global(.yn6zku7qr) {
  d: path("M8.168 3.445a1 1 0 0 1 1.664 1.11L6.869 9h10.262l-2.963-4.445a1 1 0 0 1 1.664-1.11L19.535 9H21a1 1 0 0 1 0 2h-6v9a1 1 0 0 1-2 0v-9h-2v9a1 1 0 0 1-2 0v-9H3a1 1 0 0 1 0-2h1.465Z");
}

</style>
