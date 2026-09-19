<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r0_xnfbzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-folder-special" {...props}></Icon>
<style>
:global(.r0_xnfbzn) {
  fill: currentColor;
  d: path("M22 6H12l-2-2H2v16h20zm-4.06 11L15 15.28L12.06 17l.78-3.33l-2.59-2.24l3.41-.29L15 8l1.34 3.14l3.41.29l-2.59 2.24z");
}

</style>
