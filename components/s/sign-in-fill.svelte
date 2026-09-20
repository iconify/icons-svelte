<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="iu4-0ebwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:sign-in-fill" {...props}></Icon>
<style>
:global(.iu4-0ebwo) {
  fill: currentColor;
  d: path("m141.66 133.66l-40 40A8 8 0 0 1 88 168v-32H24a8 8 0 0 1 0-16h64V88a8 8 0 0 1 13.66-5.66l40 40a8 8 0 0 1 0 11.32M200 32h-64a8 8 0 0 0 0 16h56v160h-56a8 8 0 0 0 0 16h64a8 8 0 0 0 8-8V40a8 8 0 0 0-8-8");
}

</style>
