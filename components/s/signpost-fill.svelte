<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="zs1s5i9-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:signpost-fill" {...props}></Icon>
<style>
:global(.zs1s5i9-l) {
  fill: currentColor;
  d: path("m246 117.35l-33.67 37.35a16 16 0 0 1-11.89 5.3H136v64a8 8 0 0 1-16 0v-64H40a16 16 0 0 1-16-16V80a16 16 0 0 1 16-16h80V32a8 8 0 0 1 16 0v32h64.44a16 16 0 0 1 11.89 5.3L246 106.65a8 8 0 0 1 0 10.7");
}

</style>
