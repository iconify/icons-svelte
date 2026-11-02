<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zn8kvzbob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:trash-fill-sharp" {...props}></Icon>
<style>
:global(.zn8kvzbob) {
  fill: currentColor;
  d: path("M16 2a1 1 0 0 1 1 1v2h3a1 1 0 0 1 0 2h-1v14a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1V7H4a1 1 0 0 1 0-2h3V3a1 1 0 0 1 1-1Zm-1 2H9v1h6Z");
}

</style>
