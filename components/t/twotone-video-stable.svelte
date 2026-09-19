<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yfgx4yu7h"/><path class="km4ipibra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-video-stable" {...props}></Icon>
<style>
:global(.km4ipibra) {
  fill: currentColor;
  d: path("M20 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2M4 18V6h2.95l-2.33 8.73L16.82 18zm11.62-2.39l-8.55-2.29L8.38 8.4l8.56 2.29zM20 18h-2.95l2.34-8.73L7.18 6H20z");
}

:global(.yfgx4yu7h) {
  fill: currentColor;
  d: path("m7.063 13.319l1.32-4.926l8.558 2.293l-1.32 4.926z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
