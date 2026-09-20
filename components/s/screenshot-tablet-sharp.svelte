<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eg5bd0bty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:screenshot-tablet-sharp" {...props}></Icon>
<style>
:global(.eg5bd0bty) {
  fill: currentColor;
  d: path("M1 20V4h22v16zm5-2h12V6H6zm7-1h4v-4h-1.5v2.5H13zm-6-6h1.5V8.5H11V7H7z");
}

</style>
