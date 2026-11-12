<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_pxpplcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:touchpad-fill-sharp" {...props}></Icon>
<style>
:global(.m_pxpplcy) {
  fill: currentColor;
  d: path("M2 13V5a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v8Zm0 2h9v5H3a1 1 0 0 1-1-1Zm20 0v4a1 1 0 0 1-1 1h-8v-5Z");
}

</style>
