<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rcic81-tg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-bookmark-remove" {...props}></Icon>
<style>
:global(.rcic81-tg) {
  fill: currentColor;
  d: path("M21 7h-6V5h6zm-2 3.9c-.64.13-1.32.14-2.02 0c-1.91-.38-3.47-1.92-3.87-3.83A5.02 5.02 0 0 1 14 3H5v18l7-3l7 3z");
}

</style>
