<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ojaszbctc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:square-split-vertical-fill" {...props}></Icon>
<style>
:global(.ojaszbctc) {
  fill: currentColor;
  d: path("M216 56v60a4 4 0 0 1-4 4H44a4 4 0 0 1-4-4V56a16 16 0 0 1 16-16h144a16 16 0 0 1 16 16m-4 80H44a4 4 0 0 0-4 4v60a16 16 0 0 0 16 16h144a16 16 0 0 0 16-16v-60a4 4 0 0 0-4-4");
}

</style>
