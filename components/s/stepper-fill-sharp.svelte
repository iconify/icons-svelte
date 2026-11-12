<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xl8ftbbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:stepper-fill-sharp" {...props}></Icon>
<style>
:global(.xl8ftbbjl) {
  fill: currentColor;
  d: path("M2 3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Zm5 3a1 1 0 0 0 0 2h10a1 1 0 0 0 0-2Zm12 9v2h2a1 1 0 0 1 0 2h-2v2a1 1 0 0 1-2 0v-2h-2a1 1 0 0 1 0-2h2v-2a1 1 0 0 1 2 0M3 17h6a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2");
}

</style>
