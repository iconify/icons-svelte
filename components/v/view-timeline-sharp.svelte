<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l65189boa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:view-timeline-sharp" {...props}></Icon>
<style>
:global(.l65189boa) {
  fill: currentColor;
  d: path("M3 21V3h18v18zm3-4h6v-2H6zm6-8h6V7h-6zm-3 4h6v-2H9z");
}

</style>
