<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="srk9s2h0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-auto-awesome-mosaic" {...props}></Icon>
<style>
:global(.srk9s2h0i) {
  fill: currentColor;
  d: path("M3 21h8V3H3zM21 3h-8v8h8zm-8 18h8v-8h-8z");
}

</style>
