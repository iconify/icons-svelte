<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="cira-jb5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:square-fill" {...props}></Icon>
<style>
:global(.cira-jb5q) {
  fill: currentColor;
  d: path("M224 48v160a16 16 0 0 1-16 16H48a16 16 0 0 1-16-16V48a16 16 0 0 1 16-16h160a16 16 0 0 1 16 16");
}

</style>
