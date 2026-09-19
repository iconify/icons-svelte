<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y79__c1sa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-explicit" {...props}></Icon>
<style>
:global(.y79__c1sa) {
  fill: currentColor;
  d: path("M21 3H3v18h18zm-6 6h-4v2h4v2h-4v2h4v2H9V7h6z");
}

</style>
