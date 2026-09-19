<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwdt0v2ci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-looks-6" {...props}></Icon>
<style>
:global(.fwdt0v2ci) {
  fill: currentColor;
  d: path("M11 15h2v-2h-2zM21 3H3v18h18zm-6 6h-4v2h4v6H9V7h6z");
}

</style>
