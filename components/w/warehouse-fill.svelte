<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="rowh0_fln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:warehouse-fill" {...props}></Icon>
<style>
:global(.rowh0_fln) {
  fill: currentColor;
  d: path("M240 184h-8V57.9l9.67-2.08a8 8 0 1 0-3.35-15.64l-224 48A8 8 0 0 0 16 104a8 8 0 0 0 1.69-.18l6.31-1.35V184h-8a8 8 0 0 0 0 16h224a8 8 0 0 0 0-16m-56 0H72v-16h112Zm0-32H72v-16h112Z");
}

</style>
