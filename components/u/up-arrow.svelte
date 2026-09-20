<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="x-kz1kb7j"/><path class="f6q-1gbii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:up-arrow" {...props}></Icon>
<style>
:global(.f6q-1gbii) {
  fill: var(--svg-color--fff, #fff);
  d: path("M22 29v-9h7L18 7L7 20h7v9z");
}

:global(.x-kz1kb7j) {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

</style>
