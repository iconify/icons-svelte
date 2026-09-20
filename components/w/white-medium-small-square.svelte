<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="mf580gbrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:white-medium-small-square" {...props}></Icon>
<style>
:global(.mf580gbrj) {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M29 27a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2V9a2 2 0 0 1 2-2h18a2 2 0 0 1 2 2z");
}

</style>
