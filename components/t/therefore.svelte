<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6j0kqbbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:therefore" {...props}></Icon>
<style>
:global(.h6j0kqbbf) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 6.5q0-2 2-2t2 2t-2 2t-2-2M6 15q-2 0-2 2t2 2t2-2t-2-2m10 2q0-2 2-2t2 2t-2 2t-2-2");
}

</style>
