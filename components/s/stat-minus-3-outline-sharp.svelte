<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7aj_op-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:stat-minus-3-outline-sharp" {...props}></Icon>
<style>
:global(.t7aj_op-h) {
  fill: currentColor;
  d: path("m12 21.925l-6-6l1.4-1.4L12 19.1l4.6-4.575l1.4 1.4zm0-5.95l-6-6l1.4-1.4L12 13.15l4.6-4.575l1.4 1.4zm0-5.95l-6-6l1.4-1.4L12 7.2l4.6-4.575l1.4 1.4z");
}

</style>
