<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="t81yqh3jp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:table-thin" {...props}></Icon>
<style>
:global(.t81yqh3jp) {
  fill: currentColor;
  d: path("M224 52H32a4 4 0 0 0-4 4v136a12 12 0 0 0 12 12h176a12 12 0 0 0 12-12V56a4 4 0 0 0-4-4M36 108h48v40H36Zm56 0h128v40H92Zm128-48v40H36V60ZM36 192v-36h48v40H40a4 4 0 0 1-4-4m180 4H92v-40h128v36a4 4 0 0 1-4 4");
}

</style>
