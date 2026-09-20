<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="by8kt6b-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:stop-fill" {...props}></Icon>
<style>
:global(.by8kt6b-n) {
  fill: currentColor;
  d: path("M216 56v144a16 16 0 0 1-16 16H56a16 16 0 0 1-16-16V56a16 16 0 0 1 16-16h144a16 16 0 0 1 16 16");
}

</style>
