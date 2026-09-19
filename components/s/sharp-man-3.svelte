<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uw8f57zpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-man-3" {...props}></Icon>
<style>
:global(.uw8f57zpo) {
  fill: currentColor;
  d: path("M16 7H8v8h2v7h4v-7h2zm-4-5.249L14.248 4L12 6.248L9.75 4z");
}

</style>
