<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="leprq-4jz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:view-agenda-sharp" {...props}></Icon>
<style>
:global(.leprq-4jz) {
  fill: currentColor;
  d: path("M3 21v-8h18v8zm0-10V3h18v8z");
}

</style>
