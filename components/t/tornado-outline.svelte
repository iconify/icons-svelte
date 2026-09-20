<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n5ip3tbvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:tornado-outline" {...props}></Icon>
<style>
:global(.n5ip3tbvz) {
  fill: currentColor;
  d: path("M1 3h22L12 22zm3.475 2L6.2 8h11.6l1.725-3zm2.9 5L9.1 13h5.8l1.725-3zm2.9 5L12 18l1.725-3z");
}

</style>
