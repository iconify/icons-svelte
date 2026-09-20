<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="tjgwn1b6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:toggle-right-thin" {...props}></Icon>
<style>
:global(.tjgwn1b6n) {
  fill: currentColor;
  d: path("M176 60H80a68 68 0 0 0 0 136h96a68 68 0 0 0 0-136m0 128H80a60 60 0 0 1 0-120h96a60 60 0 0 1 0 120m0-96a36 36 0 1 0 36 36a36 36 0 0 0-36-36m0 64a28 28 0 1 1 28-28a28 28 0 0 1-28 28");
}

</style>
