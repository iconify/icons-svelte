<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="x-kz1kb7j"/><path class="dvlz3bc1s"/><path class="oytv3dbmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:up-down-arrow" {...props}></Icon>
<style>
:global(.dvlz3bc1s) {
  fill: var(--svg-color--fff, #fff);
  d: path("M27 13L18 3L9 13zm-9 20l9-10H9z");
}

:global(.oytv3dbmw) {
  fill: var(--svg-color--fff, #fff);
  d: path("M14 12h8v12h-8z");
}

:global(.x-kz1kb7j) {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

</style>
