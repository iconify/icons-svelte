<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="tw-ju_bhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:text-underline-light" {...props}></Icon>
<style>
:global(.tw-ju_bhz) {
  fill: currentColor;
  d: path("M198 224a6 6 0 0 1-6 6H64a6 6 0 0 1 0-12h128a6 6 0 0 1 6 6m-70-26a62.07 62.07 0 0 0 62-62V56a6 6 0 0 0-12 0v80a50 50 0 0 1-100 0V56a6 6 0 0 0-12 0v80a62.07 62.07 0 0 0 62 62");
}

</style>
