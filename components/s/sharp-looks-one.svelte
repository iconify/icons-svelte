<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a6as2zbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-looks-one" {...props}></Icon>
<style>
:global(.a6as2zbqa) {
  fill: currentColor;
  d: path("M21 3H3v18h18zm-7 14h-2V9h-2V7h4z");
}

</style>
