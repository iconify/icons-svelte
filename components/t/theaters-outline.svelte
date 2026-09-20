<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bsu47lbet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:theaters-outline" {...props}></Icon>
<style>
:global(.bsu47lbet) {
  fill: currentColor;
  d: path("M4 21V3h2v2h2V3h8v2h2V3h2v18h-2v-2h-2v2H8v-2H6v2zm2-4h2v-2H6zm0-4h2v-2H6zm0-4h2V7H6zm10 8h2v-2h-2zm0-4h2v-2h-2zm0-4h2V7h-2zm-6 10h4V5h-4zm0-14h4z");
}

</style>
