<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1itsyb0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:view-carousel" {...props}></Icon>
<style>
:global(.g1itsyb0s) {
  fill: currentColor;
  d: path("M2 7h4v10H2zm5 12h10V5H7zM18 7h4v10h-4z");
}

</style>
