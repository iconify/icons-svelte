<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cha6q8m0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:team-dashboard" {...props}></Icon>
<style>
:global(.cha6q8m0u) {
  fill: currentColor;
  d: path("M5.616 20q-.667 0-1.141-.475T4 18.386V12.25h6.5V20zm5.884 0v-7.75H20v6.135q0 .666-.475 1.14t-1.14.475zM4 11.25V5.616q0-.667.475-1.141T5.615 4h12.77q.666 0 1.14.475T20 5.615v5.635z");
}

</style>
