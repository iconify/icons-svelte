<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_mjssbjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-announcement" {...props}></Icon>
<style>
:global(.j_mjssbjx) {
  fill: currentColor;
  d: path("M22 2H2v20l4-4h16zm-9 9h-2V5h2zm0 4h-2v-2h2z");
}

</style>
