<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wojnxfy3j"/><path class="aya9hf04n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-publish" {...props}></Icon>
<style>
:global(.aya9hf04n) {
  fill: currentColor;
  d: path("M5 4h14v2H5zm7 3l-7 7h4v6h6v-6h4zm1 5v6h-2v-6H9.83L12 9.83L14.17 12z");
}

:global(.wojnxfy3j) {
  fill: currentColor;
  d: path("M9.83 12H11v6h2v-6h1.17L12 9.83z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
