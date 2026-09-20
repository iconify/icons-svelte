<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="evs8fk9ea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:tornado-outline-rounded" {...props}></Icon>
<style>
:global(.evs8fk9ea) {
  fill: currentColor;
  d: path("M4.475 3h15.05q1.175 0 1.738 1t-.013 2l-7.525 13Q13.15 20 12 20t-1.725-1L2.75 6q-.575-1-.012-2t1.737-1m0 2L6.2 8h11.6l1.725-3zm2.9 5L9.1 13h5.8l1.725-3zm2.9 5L12 18l1.725-3z");
}

</style>
