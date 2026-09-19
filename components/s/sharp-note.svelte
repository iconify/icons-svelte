<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmv0oy0qj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-note" {...props}></Icon>
<style>
:global(.fmv0oy0qj) {
  fill: currentColor;
  d: path("m22 10l-6-6H2v16h20zm-7-4.5l5.5 5.5H15z");
}

</style>
