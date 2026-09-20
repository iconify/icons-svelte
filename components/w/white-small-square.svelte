<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="zdtxxnb1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noto-v1:white-small-square" {...props}></Icon>
<style>
:global(.zdtxxnb1b) {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("M50.04 50.04h27.91v27.92H50.04z");
}

</style>
