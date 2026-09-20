<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rza1yubxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:triangle-down-24-filled" {...props}></Icon>
<style>
:global(.rza1yubxn) {
  fill: currentColor;
  d: path("M4.253 3C2.524 3 1.441 4.87 2.302 6.37l7.744 13.502c.865 1.507 3.039 1.507 3.904 0l7.744-13.503C22.554 4.87 21.472 3 19.742 3z");
}

</style>
