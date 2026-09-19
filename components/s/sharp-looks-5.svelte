<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iacizf6un"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-looks-5" {...props}></Icon>
<style>
:global(.iacizf6un) {
  fill: currentColor;
  d: path("M21 3H3v18h18zm-6 6h-4v2h4v6H9v-2h4v-2H9V7h6z");
}

</style>
