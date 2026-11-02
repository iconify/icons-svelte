<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rls14db7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:terminal-fill-round" {...props}></Icon>
<style>
:global(.rls14db7s) {
  fill: currentColor;
  d: path("M2 9a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v6a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 20H7a5 5 0 0 1-5-5Zm5.707-.707a.999.999 0 1 0-1.414 1.414L8.586 12l-2.293 2.293a.999.999 0 1 0 1.414 1.414l3-3a1 1 0 0 0 0-1.414ZM13 14a1 1 0 0 0 0 2h4a1 1 0 0 0 0-2Z");
}

</style>
