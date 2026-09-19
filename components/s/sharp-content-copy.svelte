<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rj6xlccuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-content-copy" {...props}></Icon>
<style>
:global(.rj6xlccuw) {
  fill: currentColor;
  d: path("M16 1H2v16h2V3h12zm5 4H6v18h15zm-2 16H8V7h11z");
}

</style>
