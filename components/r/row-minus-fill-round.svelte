<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4-pn4mrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:row-minus-fill-round" {...props}></Icon>
<style>
:global(.z4-pn4mrt) {
  fill: currentColor;
  d: path("M7 3h10a4 4 0 0 1 0 8H7a4 4 0 0 1 0-8m8 13a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Z");
}

</style>
