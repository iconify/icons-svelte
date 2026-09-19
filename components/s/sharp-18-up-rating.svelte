<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fke3nsb4z"/><path class="hexsfe7at"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-18-up-rating" {...props}></Icon>
<style>
:global(.fke3nsb4z) {
  fill: currentColor;
  d: path("M13 12.5h1.5V14H13zm0-2.5h1.5v1.5H13z");
}

:global(.hexsfe7at) {
  fill: currentColor;
  d: path("M21 3H3v18h18zM10 15H8.5v-4.5H7V9h3zm6-1c0 .55-.45 1-1 1h-2.5c-.55 0-1-.45-1-1v-4c0-.55.45-1 1-1H15c.55 0 1 .45 1 1z");
}

</style>
