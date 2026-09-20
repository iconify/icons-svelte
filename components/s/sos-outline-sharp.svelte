<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qfkea-bmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:sos-outline-sharp" {...props}></Icon>
<style>
:global(.qfkea-bmy) {
  fill: currentColor;
  d: path("M8.5 17V7h7v10zM1 17v-2h4v-2H1V7h6v2H3v2h4v6zm16 0v-2h4v-2h-4V7h6v2h-4v2h4v6zm-6.5-2h3V9h-3z");
}

</style>
